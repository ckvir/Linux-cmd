ps aux              ：全部 Process

ps -p [PID] -o comm ：Get Process name 

ps -el              ：Process nice

ps -eo state,uid,pid,ppid,rtprio,time,comm  ：RealTime Process

char                ：Set Process schedule

cat /proc/cpuinfo   ：看 cpu 狀態

cat /boot/config-*  | grep CONFIG_HZ 
