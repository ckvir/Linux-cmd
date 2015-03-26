find -name xxx：搜尋檔案

grep -R -n 'xxx' --include *.c ./

- -R：遞迴
- -n：顯示行號
- --include：指定附檔名
- ./ 由目前目錄開始往下搜尋


 ls -lh
 - M for MB
 - K for KB
 - G for GB

建議： 
 
alias ll="ls -lh"

alias lv="ls -F"

alias ls="ls -F --color=auto"

USB:

mkdir /tmp/usb

mount /dev/sdc /tmp/usb/

cp *.sh /tmp/usb/

umount /tmp/usb/
