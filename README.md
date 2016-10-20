# MIDI2LR-Lightroom

You will find in this project some mapping files to make [MIDI2LR](http://rsjaffe.github.io/MIDI2LR/) works with:

1. [TouchOSC](http://hexler.net/software/touchosc-android)
2. [Midi Fighter Twister](https://store.djtechtools.com/products/midi-fighter-twister)

On my [Photography Website](http://www.mathieu.photography/Photos/Portfolio/Projets/MIDi2LR-Lightroom-Mappings), you will find some help for MIDI2LR and TouchOSC.

If you find some improvements to do, or would like to contribute a new mapping, please open an issue or send me a PR!

## TouchOSC

### Installation

Follow the TouchOSC installation on their website. You will need __TouchOSC Editor__, __TouchOSC Bridge__ running on your computer, and the __TouchOSC__ app for Android or Apple.

Follow the __MIDI2LR__ installation from their website.

__Mapping installation:__

1. Download this project's zip file [here](https://github.com/mathieucarbou/Lightroom_MIDI2LR/archive/master.zip) and unzip it.
2. Copy the presets in your Lightroom's Development Presets folder
3. `MIDI2LR_TouchOSC.xml` is the file you need to load from MIDI2LR.
4. `TouchOSC_Lightroom.touchosc` is the file you need to load from TouchOSC apps or editor. Note: this file is optimized for devices with a __resolution of 1920x1200__ (or equivalent). I tested it on Nexus 7 2013 Tablet.

__`!!! WARNING !!!`__

I am currently contributing some new features in the MIDI2LR project. So have a loot at the latest patched releases [here](https://github.com/mathieucarbou/MIDI2LR/releases/) if some features are missing / not yet integrated in the main project.

__You can download my MIDI2LR build with all my latest contributed patches [here](https://github.com/mathieucarbou/MIDI2LR-Lightroom/blob/master/LRPlugin.zip?raw=true)__

__Lightroom MIDI2LR configuration:__

1. You will need to configure MIDI2LR options in Lightroom (File menu > Plugins > Options for MIDI2LR) to match the following screenshot:

![Presets Options](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/MIDI2LR%20options%20presets.png)

![Shortcuts Options](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/MIDI2LR%20options%20shortcuts.png)

### Overview

#### Page 1: Basic

![Basic](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%201.png)

#### Page 2: Tone Curve / Black and White Mix

![Tone Curve / Black and White Mix](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%202.png)

#### Page 3: HSL

![HSL](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%203.png)

#### Page 4: Split Toning / Details

![Split Toning / Details](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%204.png)

#### Page 5: Lense Correction

![Lense Correction](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%205.png)

#### Page 6: Transform / Effects

![Transform / Effects](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%206.png)

#### Page 7: Camera Calibration / Crop

![Camera Calibration / Crop](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%207.png)

#### Page 8: Local Adjustements

![Local Adjustements](https://raw.githubusercontent.com/mathieucarbou/Lightroom_MIDI2LR/master/TouchOSC/Screenshots/TouchOSC%20Page%208.png)

#### Common Controls

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
