#遊戲說明
 
         由程式控制 8 * 8的點矩陣的輸出，同一時間點亮4 (2 * 2)個燈來模擬地鼠跳出來。當玩家按下按鈕即代表打擊，
         當所打擊的位置與燈號亮的相對位置一致即得分。

#功能說明

   1.七段顯示器控制:

        1.記分板:當打到地鼠(即按鈕位置與燈號位置相同)時，分數+1，遊戲開始時設為0。
   
        2.倒數計時:每局30秒，當時間到時畫面保持全暗、分數不再改變。
 
   2.點矩陣控制:
 
        1.由10000HZ的頻率重複掃，利用視覺暫留的效果來達成同時亮多個燈的目的。
   
        2.由內建寫好的一連串位置亮燈
 
   3.按鈕控制:
  
        1.由100HZ的頻率來檢查按鈕是否有被按下。
   
        2.當按下的位置與顯示位置相同則控制七段顯示器計分項目 +1。
 
   4.其他控制:
 
        1.按下RESET鈕後重新開始遊戲(分數歸0，計時從30開始)
   
        2.由SW1 、SW2來選擇遊戲難度，當SW1 ON 燈號更改的頻率從原本的1HZ 變成 2HZ 當SW2 ON 燈號更改的頻率從原本的2HZ 變成 4HZ
 
   影片連結:https://youtu.be/c1WYTpJIIWQ
