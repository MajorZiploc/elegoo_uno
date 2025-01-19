to get which com device is on:
Device Manager:
  Ports (should see in list)

big board settings - brand: elegoo
Board: Arduino Mega or Mega 2560
Processor: ATmega2560 (Mega 2560)

small board settings - Arduino nano
Nano is using the chips ATmega328P and CH340, Replace FT232RL.
Board: Arduino Nano
Processor: ATmega328P (Old Bootloader)
NOTE:
  may require older ch340 driver
    unzip ./drivers/CH341SER.zip
      from: https://www.arduined.eu/ch340-windows-10-driver-download/
      1. use the .exe
      2. uninstall (ch340 driver is on machines be default)
      3. install (installs v3.5)

TODO:
test PUTTY
  it is supposed to allow for headless Arduino IDE stuff
    from: https://www.youtube.com/watch?app=desktop&v=RsvScNvkosQ
