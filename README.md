# 8Bit Mixtape NEO
New Attiny85 based edition with Bootloader to program it via sound.

## Documentation and Instructions

See more documentation this wiki: https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki

## Web-Interface

Upload examples directly from the browser: https://8bitmixtape.github.io/

Convert hex2Wav in browser and talk to your synth: https://8bitmixtape.github.io/8Bit-Mixtape-NEO/webpage/

## First Working prototypes
See our first working prototype in the video: https://www.youtube.com/watch?v=9HnzJeK31R8

![Working prototype_taipei](https://github.com/8BitMixtape/8bitMixTape-SoundProg2085/blob/master/boards/FirstPrototype_Neo03/Tokyo_prototype_overview.jpg)


## Background
Inspired by the bootloader for atmega by Christoph Haberer and other implementations by Fredrik...
* http://www.hobby-roboter.de/forum/viewtopic.php?f=4&t=127
* http://www.fredrikolofsson.com/f0blog/?q=node%2F596

Not found anything yet for attiny, except that's it's a bit more challenging to make bootloaders.
* http://www.mikrocontroller.net/articles/Konzept_f%C3%BCr_einen_ATtiny-Bootloader_in_C

Can we maybe use the same bootloader to program via blinking lights?
* https://www.wayneandlayne.com/blinky_programmer/

# Bootloader in progress
see devel repo here: 
* Iyoks devel: https://github.com/ATtinyTeenageRiot/TinyAudioBoot
* forked and improved by Chris: https://github.com/ChrisMicro/TinyAudioBoot
* find all files, pre-compiled and examples by Chris: https://github.com/ChrisMicro/AttinySound

# Boards are being designed atm...

![](https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki/images/boards/Collage_boards.jpg)

![Making board in yogya](https://github.com/8BitMixtape/8bitMixTape-SoundProg2085/raw/master/boards/FirstPrototype_Neo03/AudioProgMixTape_MakingOf.png)

See more boards on the wiki: https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki/2-Boards

# Test your prototype

Notes from our first testing phase: https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki/3_5-Testing-the-prototypes

## Version 0.95 Final - Changed Sound to PB1

![](https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki/images/schematics/NeopixelV095_uwe_updates.jpg)

## Older versions

See wiki: https://github.com/8BitMixtape/8Bit-Mixtape-NEO/wiki/3_2-Schematics-Discussion

# Basic stuff we need

* 2 potentiometers
* 2 push-buttons
* 1 Sound output PWM (PB1 is preferred) is also CV output in case of Sequencer code
* Sound-progger input
* CV input (maybe 2 CV input
* Master-clock or gate output
* Sync-clock input (compatible to other voltages
* 1 pin to communicate wiht the 8 NEO-pixels (is that cheating?)
* what else? 
* mic-4 ring jacks?

# The Beginning...

Late night geeking at Iyok's ego-lab...

![Late night geeking at Iyok's ego-lab](https://github.com/8BitMixtape/8bitMixTape-SoundProg2085/raw/master/boards/FirstPrototype_Neo03/IMG_20170127_191152.jpg)

After years of geeking around wiht all these versions of 8bit Mixtapes...

http://lifepatch.org/8-bit_Mixtape

or 

http://wiki.sgmk-ssam.ch/wiki/8bit_Mix_Tape

