# COLOR_PAL_THESONDERS

There are more that VGA64 or SCART512 adaptors in the I/O BOARD ATLAS for CYC1000 and MAX1000.
Here we indicate the solution with a real COMPOSITE VIDEO for I/O BOARD ATLAS, the same way as we did in the VGA222.

COLOR_PAL
Color Video Composite PAL modulator using Verilog
Outputs: 7bits modulated output.
Use a DAC to get about 1V peak to peak with the 75 Ohm TV load.
Tested on a Philips TV from 90s.

512 Colors
Inputs: RGB (3:3:3), syncs and a 35.46 ~ 36.00 clock.
Includes a logical YUV matrix and QAM Encoder

64 Colors
Inputs: RGB (2:2:2), syncs and a 35.46 ~ 36.00 clock.
Uses a precalculated waveform

The original VERILOG code could be find here:


https://github.com/TheSonders/COLOR_PAL
