# raspberry-python-test
respberry test code using python 


## start python code on boot
```bash
sudo nano /etc/rc.local
```

append this:

```bash
sudo python /home/pi/sample.py &
```

Then reboot to test it.

## check the gpio config in config.txt
https://www.raspberrypi.com/documentation/computers/config_txt.html#gpio-control