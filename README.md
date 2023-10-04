# Storyboard Keyboard PCB

The "Storyboard" is a 5x12 ortholinear keyboard with an E-INK display in the middle. This is a hobby project so I've designed the keyboard with learning and experimentation in mind. Most components are SMT and can be assembled by the PCB manufacturer for added cost leaving only a few headers to be soldered by hand. The `production_files` directory contains gerber files and BOM needed for manufacturing.

## Features:
- Ortholinear 5x12 key arrangement.
- Hot swap key switches with split FR4 plates.
- E-Ink display for personalization. Last set image will remain even when keyboard is unplugged/powered off.
- Support for 60% keyboard cases. **NOTE:** Currently only supports O-Ring based push fit cases like the Bakeneko60.
- Support for different [Sparkfun Micromod](https://www.sparkfun.com/micromod) processor boards allowing for easy swap of the underlying MCU and related functionality (requires firmware change).
- Shift register based key matrix that requires only 4 GPIOs. Also potentially supports SPI based reads/writes, but as of writing this is untested.
- Key press interrupt support to enable lower power usage modes.
- USB daughterboard support (e.g. [Unified Daughterboard](https://github.com/Unified-Daughterboard/)).

## Inspiration:
- [Lumberjack](https://github.com/peej/lumberjack-keyboard)
- [Ghoul](https://github.com/tzarc/ghoul)
- [Bakeneko 60](https://github.com/kkatano/bakeneko-60)

## Pictures
![storyboard-rev1-keys](https://github.com/cbskii/storyboard-keyboard/assets/16770076/baa4a0dd-6e3a-4830-8398-851ce99656bf)
![storyboard-rev1-front](https://github.com/cbskii/storyboard-keyboard/assets/16770076/1539c134-f4d8-4b7b-94f2-d11e5dc67efb)
![storyboard-rev1-back](https://github.com/cbskii/storyboard-keyboard/assets/16770076/7c4fc81d-7380-4ae1-8a54-98725b1e2470)

