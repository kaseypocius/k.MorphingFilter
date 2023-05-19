# k.MorphingFilter
 A rough clone of the Doepfer A-107 Multitype Morphing Filter, to be run in a bpatcher.

 Save up to 32 presets of the cascade filter UI, and interpolate between them. Waveshapping on the inputs and outputs to model/build upon behaviour from the [Doepfer A-107](https://doepfer.de/a100_man/A107_man.pdf)

 Has 4 inlets
 1 - Audio In
 2 - Input Gain (0 - 1, scaled from 0 - 10 with an exponential curve of 0.125)
 3 - Preset Interpolation (0 - 32, Float for smooth interpolation or Int for stepped)
 4 - Output Gain (0 - 1, scaled from 0 - 10 with an exponential curve of 0.125)

The MC version takes one arguments, which is the number of channels.