# Dual 3340 VCO
This module implements two CEM3340/AS3340 VCO ICs, with front panel pulse width and coarse and fine pitch controls, and linear FM, 1V/octave, switchable hard sync (positive/negative/both), and attenuated PWM inputs.
The 1V/octave inputs are connected to each other via switching jacks, so you can control the pitch of the oscillators simultaneously. (Will need to test for pitch slackening with this.) 
\[This functionality can be customized by soldering only one of the 1V/oct input jacks' switch pins, or removed by soldering neither.\]
All outputs are re-centered and normalized to ±5V. A waveshaping circuit based on [Thomas Henry's VCO-1](https://www.birthofasynth.com/Thomas_Henry/Pages/VCO-1.html) provides a sine output. 
The switchable hard sync uses the hard-sync diode circuit from [the original Curtis Electromusic datasheet.](https://www.curtiselectromusic.com/family-law.html)
The module also implements the chip-to-chip soft synchronization described in the original datasheet, wth front-panel switches for each oscillator. Turning on the switch corresponding to each oscillator causes that oscillator to be synchronized by the other, so you can select sync either way, no sync, or mutual sync.

## Construction
<details><summary>View build instructions</summary>
  
  
</details>

## Calibration

