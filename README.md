# Storyboard Keyboard PCB

The "Storyboard" is a 5x12 ortholinear keyboard with an E-INK display in the middle. This is a hobby project so I've designed the keyboard with learning and experimentation in mind. Most components are SMT and can be assembled by the PCB manufacturer for added cost leaving only a few headers to be soldered by hand. The `production_files` directory contains gerber files and BOM needed for PCB manufacturing.

## Features
- Ortholinear 5x12 key arrangement (size of standard 60% keyboard).
- Hot swap key switches with split FR4 plates.
- QMK firmware ([development branch](https://github.com/cbskii/qmk_firmware/tree/master/keyboards/storyboard)).
- E-Ink display for personalization ([3.52" Waveshare e-Paper HAT](https://www.waveshare.com/3.52inch-e-paper-hat.htm)). Last set image will remain even when keyboard is unplugged/powered off.
- Support for different [Sparkfun Micromod](https://www.sparkfun.com/micromod) processor boards allowing for easy swap of the underlying MCU and related functionality (requires firmware change).
- Shift register based key matrix that requires only 4 GPIOs.
- Key press interrupt support to enable lower power usage modes.
- USB daughterboard support (e.g. [Unified Daughterboard](https://github.com/Unified-Daughterboard/)).

## Inspiration
- [Lumberjack](https://github.com/peej/lumberjack-keyboard)
- [Ghoul](https://github.com/tzarc/ghoul)
- [Bakeneko 60](https://github.com/kkatano/bakeneko-60)

## Pictures
![storyboard-space](https://github.com/cbskii/storyboard-keyboard/assets/16770076/8a669d00-ad63-478d-9b16-c08ad3f82c0a)
![storyboard-flowers](https://github.com/cbskii/storyboard-keyboard/assets/16770076/1a8f4385-c322-4843-b1c1-cc1ccb8687ff)
![storyboard-rev1-front](https://github.com/cbskii/storyboard-keyboard/assets/16770076/1539c134-f4d8-4b7b-94f2-d11e5dc67efb)
![storyboard-rev1-back](https://github.com/cbskii/storyboard-keyboard/assets/16770076/7c4fc81d-7380-4ae1-8a54-98725b1e2470)

