# Storyboard Keyboard PCB

The "Storyboard" is a 5x12 ortholinear keyboard with an E-Paper display in the middle. This is a hobby project so I've designed the keyboard with learning and experimentation in mind. Most components are SMT and can be assembled by the PCB manufacturer for added cost leaving only a few headers to be soldered by hand. The `production_files` directory contains gerber files and a BOM needed for PCB manufacturing.

## Features
- Ortholinear "split" 5x12 key arrangement.
- Hot swap key switches with split FR4 plates.
- Fits standard sized 60% keyboard cases that use a USB daughterboard (e.g. Tofu60 and Bakeneko60).
- E-Paper display for personalization. The [3.7" Waveshare e-Paper HAT](https://www.waveshare.com/3.7inch-e-paper-hat.htm)) fits the best and is supported by the firmware, but the 3.52" would work as well if firmware support is added. Last set image will remain even when keyboard is unplugged/powered off (but recommended to refresh the display every now and then by rebooting the keyboard).
- USB daughterboard support (e.g. [Unified Daughterboard](https://github.com/Unified-Daughterboard/)).
- Support for different [Sparkfun Micromod](https://www.sparkfun.com/micromod) processor boards allowing for easy swap of the underlying MCU and related functionality (requires firmware change).
- QMK firmware ([development branch](https://github.com/cbskii/qmk_firmware/tree/master/keyboards/storyboard)).
- Shift register based key matrix that requires only 4 GPIOs.
- Key press interrupt support to enable lower power usage modes.

## Inspiration
- [Lumberjack](https://github.com/peej/lumberjack-keyboard)
- [Ghoul](https://github.com/tzarc/ghoul)
- [Bakeneko 60](https://github.com/kkatano/bakeneko-60)

## Pictures
![storyboard-rev1-keys](https://github.com/cbskii/storyboard-keyboard/assets/16770076/baa4a0dd-6e3a-4830-8398-851ce99656bf)
![storyboard-rev1-front](https://github.com/cbskii/storyboard-keyboard/assets/16770076/1539c134-f4d8-4b7b-94f2-d11e5dc67efb)
![storyboard-rev1-back](https://github.com/cbskii/storyboard-keyboard/assets/16770076/7c4fc81d-7380-4ae1-8a54-98725b1e2470)

