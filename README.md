# Generic-Segment-Displayer-VHDL

### What each input means:


`Clk_frequency` is the frequency of the clock you feed it in ports. (Measured in Hertz)

`Digit_count` is how many digits you have on your board.

`Refresh_cycle_hz` is the frequency at which you want to refresh the display.

`Segment_count` is how many segments does each digit have.

`Active` represents the logic used in the seven segment display ( 0 => active low, 1 => active high).

`Seven_seg_info` is the total digit information you pass to it.

`Clk` is the clock.

`Rst` is the reset.

`Current_digit` is the multiplexed digit.

`Digit_selection` is the decoded digit.

