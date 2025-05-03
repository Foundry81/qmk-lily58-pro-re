# Lily58 Pro RE
 Custom QMK firmware used for a batch of Lily58 Pro RE keyboard boards including the [Drew Hackworth](https://www.instagram.com/p/C6Rc3s0AkFb/) and [Cinnamon Rolls Royce](https://www.reddit.com/r/ErgoMechKeyboards/comments/1ce5y0o/lily58_pro_re/).

## config.h
- Encoder support for both sides.
- RGB underglow support - 14 LEDs per side.
 
LED support is disabled by default.
Adding LEDs? Enable RGB in rules.mk and then edit the RGB_NUM and RGBLED_SPLIT values in this file.

## rules.mk
| Feature | Enabled |
| --- | --- |
| OLEDs | ✅ |
| VIA | ✅ |
| MOUSEKEY |❌ |
| ENCODERS | ✅✅ |
| EXTRAKEY | ✅ |
| LTO | ✅ | 
|RGB |❌|   

## keymap
standard keymap with OLED and encoder enhancements.

### oled output
- left screen = status (computer type, modifier status)
- light screen = branding (3 foxagrams)

### encoders

#### left
- clockwise - redo (ctrl-y)
- counter-clockwise - undo (ctrl-z) 

(while holding RSE down)
- clockwise - alt-tab-right (windows window selector)
- counter-clockwise - alt-tab-left  (windows window selector)

#### right
- clockwise - volume up
- counter-clockwise - volume down

## Questions?
Find me in the [Lawrence Systems Discord](http://lawrence.video/discord).