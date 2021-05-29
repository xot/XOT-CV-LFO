# XOT-CV-LFO

Max for Live MIDI effect. CV LFO effect adding a unipolar/bipolar mode switch. 

(c) Jaap-Henk Hoepman (info@xot.nl)

## Description

![Screenshot](Screenshot.png "Screenshot")

This effect is a simple adaptation from Ableton Live's CV LFO effect adding a unipolar/bipolar mode switch. 

In *bipolar* mode (as the original effect implements), the LFO oscillates around the offset. As a result the offset corresponds to the mean output of the oscillator, which is stable even when the depth is modulated. 

In *unipolar* mode (new), the LFO oscillates between offset and offset + depth, in other words the LFO signal is added to the offset. This guarantees that the offset always corresponds to the lowest signal output of the LFO, even when the depth is modulated.

With this modification, the CV LFO effect is more easily used in modular rack style synthesis setups.
