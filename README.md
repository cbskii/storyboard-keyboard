# Storyboard Keyboard PCB
**Work in Progress - untested!**

The "Storyboard" is a small ortholinear keyboard with an E-INK display in the middle. This is a hobby project so I've designed the keyboard with learning and experimentation in mind, not cost.

Features:
- Ortholinear 5x12 key arrangement.
- E-Ink display for personalization.
- Support for 60% keyboard cases.
- Support for different [Sparkfun Micromod](https://www.sparkfun.com/micromod) processor boards allowing for easy swap of the underlying MCU and related functionality.
- Shift register based key matrix that can use SPI or only 4 GPIOs.
- Key press interrupt support to enable lower power usage modes.
- USB daughterboard support (e.g. [Unified Daughterboard](https://github.com/Unified-Daughterboard/))

Inspiration:
- [Lumberjack](https://github.com/peej/lumberjack-keyboard)
- [Ghoul](https://github.com/tzarc/ghoul)
- [Bakeneko 60](https://github.com/kkatano/bakeneko-60)
