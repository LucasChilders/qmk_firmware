# lucaschilders gmmk pro rev1 layout

Based on [gmmk/pro/rev1/ansi/keymaps/default](../default/keymap.c)

Layer 0
- Rotary encoder is configured for previous and next track. Push is play / pause
- Print Screen is now play / pause (key between F12 and rotary)

Layer 1
- Bootloader is backslash key (below backspace)
- LED brightness control is arrow up / down
- LED hue is arrow left / right
- LED static mode is END key
- LED toggle is Print Screen

LEDS
- Static by default
- 10 minute timeout
- Sleep LEDs on system sleep

Compile with `qmk compile -kb gmmk/pro -km lucaschilders`