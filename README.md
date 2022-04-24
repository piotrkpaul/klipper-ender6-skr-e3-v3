# klipper-ender6-skr-e3-v3
Klipper configuration for Ender 6 running on SKR E3 V3.0 board with BlTouch and BIQU H2

**DISCLAIMER: I had issues with mirrored prints (in X axis). You have to swap X and Y cables on a motherboard in order to work properly.**

Configuration overview:
1. **Printer**: Ender 6
2. **Motherboard**: BTT SKR Mini E3 V3.0 with TMC 2209 drivers in UART mode
3. **Hotend and extruder**: BIQU H2 v1
4. **Probe:** BLTouch
5. **Camera:** Logitech C920 HD webcam
6. **Input Shaper** configured with ADXL345 (connected to Raspberry Pi 4B)


Fans overview:
**FAN0:** hotend fan

**FAN1:** part cooling fan

**FAN2:** board fan



Created to be compatible with versions below:

**fluidd**: v1.17.2

**klipper**: v0.10.0-368-g4a8a76ea

**moonraker**: v0.7.1-546-g47c6245
