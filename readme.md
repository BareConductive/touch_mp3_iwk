[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Touch MP3 for IWK code

Simple touch-to-MP3 code for the [Bare Conductive Interactive Wall Kit](http://www.bareconductive.com/shop/interactive-wall-kit/). This is a slightly modified version of the Touch MP3 code.

You need twelve MP3 files named TRACK000.mp3 to TRACK011.mp3 in the root of the microSD card. 
 
When you touch electrode E0, TRACK000.mp3 will play. When you touch electrode E1, TRACK001.mp3 will play, and so on.

    SD card    
    │
      TRACK000.mp3  
      TRACK001.mp3  
      TRACK002.mp3  
      TRACK003.mp3  
      TRACK004.mp3  
      TRACK005.mp3  
      TRACK006.mp3  
      TRACK007.mp3  
      TRACK008.mp3  
      TRACK009.mp3  
      TRACK010.mp3  
      TRACK011.mp3  

## Requirements
* You should make sure that you have followed our [How to set up the Touch Board with Arduino for the Interactive Wall Kit](http://www.bareconductive.com/make/how-to-set-up-the-touch-board-with-arduino-for-the-interactive-wall-kit) tutorial before using this (or any other) of our code examples


## Install

1. Close the Arduino IDE if you have it open.
1. Download the [.zip](https://github.com/BareConductive/touch_mp3_iwk/archive/public.zip) or clone the repository to your local machine - if downloading the .zip, extract the contents somewhere that suits you.
1. Take the **Touch_MP3_IWK** folder and move it to **Arduino Sketchbook Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino
	
	or
	
	My Documents\\Arduino	
	
	**Mac**
	
	Documents/Arduino
	
	**Linux (Ubuntu)**
	
	Home/Arduino


	If this folder does not exist, create it first.
1. Reopen the Arduino IDE - you should now be able to open the sketch in the **File -> Sketchbook** menu.
