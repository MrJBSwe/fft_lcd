# fft_lcd

Prerequsites
https://github.com/kendryte

build
cmake .. -DPROJ=fft_lcd -DTOOLCHAIN=/opt/kendryte-toolchain/bin && make
 
flash
sudo python3 kflash.py -p /dev/ttyUSB0 fft_lcd.bin

