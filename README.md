# fft_lcd

Prerequsites toolchain
https://github.com/kendryte

Test of HW FFT with Kendryte K210 / Sipeed M1 dock

build
cmake .. -DPROJ=fft_lcd -DTOOLCHAIN=/opt/kendryte-toolchain/bin && make
 
flash
sudo python3 kflash.py -p /dev/ttyUSB0 fft_lcd.bin

