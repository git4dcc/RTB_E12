# RTB_E12
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Kicad_Libs](https://img.shields.io/badge/Kicad_Libs-29C7FF)](https://github.com/git4dcc/RTB_SamacSys)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

This E12 module is designed for signal socket imbedding and implements a 12 channel WS2811. The E12 may be cascaded with regular WS28xx chips. The number of LEDs is fixed to 12.

```
Byte order:     {led_0} ... {led_11}
```

The decoder has the following features,
- **Protocol**
  - WS2811 chip timing
- **LED ports**
  - 12 channel output (4x WS2811 chips)
  - Common LED voltage +5V
  - Drives common anode
  - 25 step PWM

[more](https://rtb4dcc.de/hardware/modules/e12/)

# PCB
<img src="https://rtb4dcc.de/wp-content/uploads/2024/02/E12_1.png" width=500>

- 4-layer PCB, FR4, 1.0mm, 18x6mm
- CPU: none (native WS2811 chips)
- BUS: WS2811
- LED: Pull
<br>

[Schematic](doc/E12_schematic.pdf) | [Layout](doc/E12_layout.pdf)
