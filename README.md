# Lightroom_MIDI2LR Mappings

You will find in this project some mapping files to make [MIDI2LR](http://rsjaffe.github.io/MIDI2LR/) works with:

1. [TouchOSC](http://hexler.net/software/touchosc-android)
2. [Midi Fighter Twister](https://store.djtechtools.com/products/midi-fighter-twister)

If you find some improvements to do, or would like to contribute a new mapping, please open an issue or send me a PR!

## TouchOSC

### Installation

Follow the TouchOSC installation on their website. You will need __TouchOSC Editor__, __TouchOSC Bridge__ running on your computer, and the __TouchOSC__ app for Android or Apple.

Follow the __MIDI2LR__ installation from their website.

Mapping installation:

1. Download this project's zip file [here](https://github.com/mathieucarbou/Lightroom_MIDI2LR/archive/master.zip) and unzip it.
2. Copy the presets in your Lightroom's Development Presets folder
3. `MIDI2LR_TouchOSC.xml` is the file you need to load from MIDI2LR.
4. `TouchOSC_Lightroom.touchosc` is the file you need to load from TouchOSC apps or editor. Note: this file is optimized for devices with a __resolution of 1920x1200__ (or equivalent). I tested it on Nexus 7 2013 Tablet.

Lightroom MIDI2LR configuration:

1. You will need to configure MIDI2LR options in Lightroom (File menu > Plugins > Options for MIDI2LR) to match the following screenshot:

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/MIDI2LR%20options%20presets.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/MIDI2LR%20options%20presets.png)

### Overview

__Page 1: Basic__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%201.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%201.png)

__Page 2: Tone Curve / Black and White Mix__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%202.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%202.png)

__Page 3: HSL__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%203.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%203.png)

__Page 4: Split Toning / Detail__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%204.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%204.png)

__Page 5: Lense Correction__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%205.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%205.png)

__Page 6: Transform__

_Comming soon!_

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%206.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%206.png)

__Page 7: Effects / Camera Calibration__

![https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%207.png](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%207.png)

__Common Controls__

Every page has a footer with common controls for:

- Next photo
- Previous photo
- Copy settings
- Paste selected settings
- Undo / Redo
- Refresh the MIDI controller if they are not in SYNC with Lightroom

### Comments

1. I do not use encoders: faders are more precise and usable on phones and tablets, but take more space and lead to a worse UI. Encoders are beautiful, but harder to use quickly.

2. On some devices, you might require the use of a stylus pen!

## Midi Fighter Twister
