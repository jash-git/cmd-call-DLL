CMD(命令 bat 模式) 執行 DLL [Rundll32.exe 與 Rundll.exe]

資料來源: https://www.cnblogs.com/DeeLMind/p/7356937.html

GITHUB: https://github.com/jash-git/cmd-call-DLL

Rundll32.exe與Rundll.exe的區別就在於前者是呼叫32位的鏈結庫，而後者是運用於16位的鏈結庫

REM rundll32.exe  dll 路径 , 函数名 参数
Rundll32.exe CB_BaseLib.dll,Add 3 5

只能呼叫執行，但無法正確傳入/傳出參數，但是傳入和傳出參數可以利用檔案來克服
