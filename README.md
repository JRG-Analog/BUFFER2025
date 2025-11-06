# BUFFER2025
A high current open loop buffer
Board is designed to use 40x40x100mm aluminum heatsink, with 40mm square fan for cooling. 

Description: 
The circuit is an open loop buffer, that is, no feedback. Phase shift induced by load impedance does not affect stability. This was originally built to test PSRR on devices which require an input capacitor, but it can be used for many other experiments.

Performance: 
  IOUT ±10A; 
  BW 60MHz, rl = 0.5Ω, 1VRMS, +8V/-3V;
  ZOUT = 250mΩ

Usage: 
Connect to power supply with current capability to match expected load. The each supply should be set to 3V more than the expected swing. For example, for a 0V to 5V squarewave use +8V and -3V. Connect the input to a function generator. This is high impedance input, so most function generators will have 2x the expected output voltage. Use short heavy cables to conect to the load.
