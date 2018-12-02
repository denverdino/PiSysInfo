# Raspberry Pi PCD8544 SysInfo Display

1. Build wiringPi

ref: http://wiringpi.com/wiringpi-and-the-raspberry-pi-compute-board/

```
cd ~
git clone git://git.drogon.net/wiringPi
cd wiringPi
./build
```

2. Build

```
cc -o pcd8544_rpi pcd8544_rpi.c PCD8544.c  -L/usr/local/lib -lwiringPi
```


3. Run

```
sudo ./pcd8544_rpi
```
