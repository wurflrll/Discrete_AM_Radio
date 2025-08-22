# Discrete AM Radio

## 27MHz AM Radio from Discrete Components

# Descriptions
This project comprises two different PCBs, a Receiver and Transmitter.  The circuits rely on basic BJT amplifier designs, a 27MHz oscillator.
###### This is a Heading h6


## Added Files
This contains all the files from my two KiCad project and the BOMS (factory assembled unlike Sawtooth generator project).

## Problems
Crystal Oscillator has issues because the loop gain is too high, due to a mispredicted Q factor of
the crystal.

Trying to use a simple op-amp circuit for the preamplification of the microphone signal was a bad idea.  
The NCS20072D is simply too high noise, especially for a high gain pre-amp from a ~-50dB microphone.
