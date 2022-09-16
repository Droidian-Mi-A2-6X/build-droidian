# Build Droidian
Build Droidian boot.img and packages from kernel repo.

### Xiaomi Mi A2
Upon black screen on boot, you should `SSH` into the device by using the following command while the device is connected to PC using USB. The password is `1234`

`ssh droidian@10.15.19.82`

After that you should run

`sudo -i`

`echo 100 > /sys/class/leds/lcd-backlight/brightness && exit`

`wget https://github.com/Droidian-Mi-A2-6X/droidian-tweaks/raw/master/setup.sh && chmod +x setup.sh && ./setup.sh`
