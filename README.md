# rpi_zram
script to enable zram for raspberry pi

Download the script and copy to /usr/bin/ folder
> sudo wget -O /usr/bin/zram.sh https://raw.githubusercontent.com/novaspirit/rpi_zram/master/zram.sh

make file executable
> sudo chmod +x /usr/bin/zram.sh

edit /etc/rc.local file to run script on boot
> sudo nano /etc/rc.local

add line before exit 0
> /usr/bin/zram.sh &

https://www.youtube.com/watch?v=IBNZLREqBxg
https://www.youtube.com/watch?v=CJ4VAelq-wE

