## My keymap for Sofle Choc

- Used the following command to flash left and right halves
    - `qmk flash -kb sofle_choc -km <Profile> -e CONVERT_TO=bit_c_pro -bl uf2-split-left && qmk flash -kb sofle_choc -km <Profile> -e CONVERT_TO=bit_c_pro -bl uf2-split-right`
    - `qmk flash -kb sofle_choc -km Lizardbutt -e CONVERT_TO=bit_c_pro -bl uf2-split-left && qmk flash -kb sofle_choc -km Lizardbutt -e CONVERT_TO=bit_c_pro -bl uf2-split-right`

## HSV Color modes (In Order)

| Index | Mode                                 | Comment                                                                                                       |
| ---   | ---                                  | ---                                                                                                           |
| 0     | RGB_MATRIX_NONE                      |                                                                                                               |
| 1     | RGB_MATRIX_SOLID_COLOR               | Static single hue, no speed support                                                                           |
| 2     | RGB_MATRIX_ALPHAS_MODS               | Static dual hue, speed is hue for secondary hue                                                               |
| 3     | RGB_MATRIX_GRADIENT_UP_DOWN          | Static gradient top to bottom, speed controls how much gradient changes                                       |
| 4     | RGB_MATRIX_GRADIENT_LEFT_RIGHT       | Static gradient left to right, speed controls how much gradient changes                                       |
| 5     | RGB_MATRIX_BREATHING                 | Single hue brightness cycling animation                                                                       |
| 6     | RGB_MATRIX_BAND_SAT                  | Single hue band fading saturation scrolling left to right                                                     |
| 7     | RGB_MATRIX_BAND_VAL                  | Single hue band fading brightness scrolling left to right                                                     |
| 8     | RGB_MATRIX_BAND_PINWHEEL_SAT         | Single hue 3 blade spinning pinwheel fades saturation                                                         |
| 9     | RGB_MATRIX_BAND_PINWHEEL_VAL         | Single hue 3 blade spinning pinwheel fades brightness                                                         |
| 10    | RGB_MATRIX_BAND_SPIRAL_SAT           | Single hue spinning spiral fades saturation                                                                   |
| 11    | RGB_MATRIX_BAND_SPIRAL_VAL           | Single hue spinning spiral fades brightness                                                                   |
| 12    | RGB_MATRIX_CYCLE_ALL                 | Full keyboard solid hue cycling through full gradient                                                         |
| 13    | RGB_MATRIX_CYCLE_LEFT_RIGHT          | Full gradient scrolling left to right                                                                         |
| 14    | RGB_MATRIX_CYCLE_UP_DOWN             | Full gradient scrolling top to bottom                                                                         |
| 15    | RGB_MATRIX_CYCLE_OUT_IN              | Full gradient scrolling out to in                                                                             |
| 16    | RGB_MATRIX_CYCLE_OUT_IN_DUAL         | Full dual gradients scrolling out to in                                                                       |
| 17    | RGB_MATRIX_RAINBOW_MOVING_CHEVRON    | Full gradient Chevron shapped scrolling left to right                                                         |
| 18    | RGB_MATRIX_CYCLE_PINWHEEL            | Full gradient spinning pinwheel around center of keyboard                                                     |
| 19    | RGB_MATRIX_CYCLE_SPIRAL              | Full gradient spinning spiral around center of keyboard                                                       |
| 20    | RGB_MATRIX_DUAL_BEACON               | Full gradient spinning around center of keyboard                                                              |
| 21    | RGB_MATRIX_RAINBOW_BEACON            | Full tighter gradient spinning around center of keyboard                                                      |
| 22    | RGB_MATRIX_RAINBOW_PINWHEELS         | Full dual gradients spinning two halfs of keyboard                                                            |
| 23    | RGB_MATRIX_FLOWER_BLOOMING           | Full tighter gradient of first half scrolling left to right and second half scrolling right to left           |
| 24    | RGB_MATRIX_RAINDROPS                 | Randomly changes a single key's hue                                                                           |
| 25    | RGB_MATRIX_JELLYBEAN_RAINDROPS       | Randomly changes a single key's hue and saturation                                                            |
| 26    | RGB_MATRIX_HUE_BREATHING             | Hue shifts up a slight ammount at the same time, then shifts back                                             |
| 27    | RGB_MATRIX_HUE_PENDULUM              | Hue shifts up a slight ammount in a wave to the right, then back to the left                                  |
| 28    | RGB_MATRIX_HUE_WAVE                  | Hue shifts up a slight ammount and then back down in a wave to the right                                      |
| 29    | RGB_MATRIX_PIXEL_FRACTAL             | Single hue fractal filled keys pulsing horizontally out to edges                                              |
| 30    | RGB_MATRIX_PIXEL_FLOW                | Pulsing RGB flow along LED wiring with random hues                                                            |
| 31    | RGB_MATRIX_PIXEL_RAIN                | Randomly light keys with random hues                                                                          |
| 32    | RGB_MATRIX_TYPING_HEATMAP            | How hot is your WPM!                                                                                          |
| 33    | RGB_MATRIX_DIGITAL_RAIN              | That famous computer simulation                                                                               |
| 34    | RGB_MATRIX_SOLID_REACTIVE_SIMPLE     | Pulses keys hit to hue & value then fades value out                                                           |
| 35    | RGB_MATRIX_SOLID_REACTIVE            | Static single hue, pulses keys hit to shifted hue then fades to current hue                                   |
| 36    | RGB_MATRIX_SOLID_REACTIVE_WIDE       | Hue & value pulse near a single key hit then fades value out                                                  |
| 37    | RGB_MATRIX_SOLID_REACTIVE_MULTIWIDE  | Hue & value pulse near multiple key hits then fades value out                                                 |
| 38    | RGB_MATRIX_SOLID_REACTIVE_CROSS      | Hue & value pulse the same column and row of a single key hit then fades value out                            |
| 39    | RGB_MATRIX_SOLID_REACTIVE_MULTICROSS | Hue & value pulse the same column and row of multiple key hits then fades value out                           |
| 40    | RGB_MATRIX_SOLID_REACTIVE_NEXUS,     | Hue & value pulse away on the same column and row of a single key hit then fades value out                    |
| 41    | RGB_MATRIX_SOLID_REACTIVE_MULTINEXUS | Hue & value pulse away on the same column and row of multiple key hits then fades value out                   |
| 42    | RGB_MATRIX_SPLASH                    | Full gradient & value pulse away from a single key hit then fades value out                                   |
| 43    | RGB_MATRIX_MULTISPLASH               | Full gradient & value pulse away from multiple key hits then fades value out                                  |
| 44    | RGB_MATRIX_SOLID_SPLASH              | Hue & value pulse away from a single key hit then fades value out                                             |
| 45    | RGB_MATRIX_SOLID_MULTISPLASH         | Hue & value pulse away from multiple key hits then fades value out                                            |
| 46    | RGB_MATRIX_STARLIGHT                 | LEDs turn on and off at random at varying brightness, maintaining user set color                              |
| 47    | RGB_MATRIX_STARLIGHT_DUAL_HUE        | LEDs turn on and off at random at varying brightness, modifies user set hue by +- 30                          |
| 48    | RGB_MATRIX_STARLIGHT_DUAL_SAT        | LEDs turn on and off at random at varying brightness, modifies user set saturation by +- 30                   |
| 49    | RGB_MATRIX_RIVERFLOW                 | Modification to breathing animation, offset's animation depending on key location to simulate a river flowing |
| 50    | RGB_MATRIX_EFFECT_MAX                | I have no fucking clue                                                                                        |