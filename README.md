# PiBoy DMG - On-Screen Display Material Icons

Alternative on-screen display icons for Experimental Pi's PiBoy DMG.
The pack is based on Google's Material Icon set, that can be found on Android. Icons have white outline and semi-transparent dark background, so they can be visible in every scene. Volume icon notification is reduced to a volume bar.
Features:
  - works on any background
  - new volume notification
  - icons based on Google's Material Icons


![1](https://user-images.githubusercontent.com/92209505/141120091-98526253-3d57-48f0-aa2b-501cb64c9f71.png)

## Screenshots:

![2](https://user-images.githubusercontent.com/92209505/141121162-dd96b110-4e43-4921-b7eb-84357b9e10de.png)

![4](https://user-images.githubusercontent.com/92209505/141121179-c276dab5-3c21-431d-acab-75fa295f4f53.png)

*Images taken from Sonic the Hedgehog 2 and Sonic Generations.

## Instalation:
A. During installing/updating the firmware
  1. Update the SD card through ExperimentalPi Utility (don't disconnect the SD card from the computer!).
  1. Copy and replace the "osd" folder to the location on your SD card:
     /boot/payload/home/pi/
  2. Disconnect the SD card and insert to the PiBoy DMG.

B. After installing the firmware
  1. Navigate to /home/pi/
  2. Copy and replace the "osd" folder using the one from the repo.

## Configuration:
Adjust the icons' positions in the osd.cfg file. I suggest using distances provided below:
    small   18px
    medium  27px
    large   36px
    
Example (large):
    throttle  496
    bluetooth 532
    wifi      568
    battery   604
