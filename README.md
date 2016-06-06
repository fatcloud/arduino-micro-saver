# arduino-micro-saver
此 repo 用於解救被寫入會擾亂鍵盤的壞壞程式的 arduino micro

先安裝 ino
http://inotool.org/#installation

然後執行 microsaver.sh
十秒後會將程式燒入 /dev/ttyACM0 （可於 ino.ini 內修改）
只要在十秒內把畫面切到一個文字編輯器（或任何不怕鍵盤干擾的程式）
再再將有問題的 arduino micro 插上，等待十秒後程式被覆寫掉即可
