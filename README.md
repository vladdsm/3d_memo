# 3d_memo
 notes about 3d printing


## What is needed

1. Arduino IDE downloaded at https://www.arduino.cc
2. Firmware for 3d printer, driver to connect to the printer
3. 3d design software
4. 'Slicer' software e.g. cura

## Firmware for 3 d printer

* Instructions at https://www.youtube.com/watch?v=5xeo9G3kXEQ
* marlin firmware see forked repo: https://github.com/vladdsm/anet-board
* marlin source code http://marlinfw.org/meta/download/

- copy example configuration to folder Marlin

## Connecting to 3d Anet with USB kable

- allow the installation see https://www.imore.com/how-open-apps-anywhere-macos-catalina-and-mojave
- install the drive from /Users/vladdsm/Documents/s3_A8/usb_content/English Instructions/Software/CH340G Drive/CH341SER_MAC


## Tips

* print the temperature calibration 'tower' (decrease temperature each 1cm by 10C
* adjust flow by printing 15x15mm cubes with 0.4mm thickness (may add e.g. 109%) set it in cura software
* set up the heating bed temperature normally about 64C
* cut the glass to put in with metal paper clips. Apply the hair spray (to stick the glass )
* print the gears on pulleys as it is generates vibration https://www.youtube.com/watch?v=O79skgl8uzc
*