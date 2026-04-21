Matrix keypad
--------------
I2CKeyPad - library for matrix keypad using I2C PCF8574 CHIP
also requires, wire.h and keypad.h, libraries to work

The Keypad is connected to ESP32 via U12, a PCF8574 with address 0x3D.

Upload the code and open Serial Monitor.

Press any key on the keypad. If the key value is printed on Serial monitor, it means the device is working as intended.

