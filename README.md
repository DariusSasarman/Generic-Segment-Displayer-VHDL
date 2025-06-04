# Generic-Segment-Displayer-VHDL

### What each input means:

- `Clk_frequency` – Frequency of the input clock (in Hertz).
- `Digit_count` – Number of digits on the display.
- `Refresh_cycle_hz` – Refresh rate of the display (in Hertz).
- `Segment_count` – Number of segments per digit.
- `Active` – Logic level used by the display (`0` = active low, `1` = active high).
- `Seven_seg_info` – Combined information for all digits to display.
- `Clk` – Clock signal.
- `Rst` – Reset signal.
- `Current_digit` – Currently active digit (used in multiplexing).
- `Digit_selection` – Digit select line output (decoder-controlled).

---

### 🎥 Live Demonstration:

[![Watch the demo](https://img.shields.io/badge/Video-Demo-blue?logo=youtube)](https://github.com/user-attachments/assets/16f8c106-278f-4839-9843-15e6539a8bc0)

<sub>Note: Shifting logic not included in Generig-Segment-Displayer code. It's implemented in the test file.</sub>
