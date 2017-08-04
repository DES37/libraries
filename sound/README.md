# Processing Sound Library

Open an issue that Spectrum and FFTSpectrum are duplicate examples!



Requires Processing 3.0+

There is a nice [sound tutorial](https://processing.org/tutorials/sound/) which discusses theory and use of the Sound library.

The Sound library can be used for audio synthesis, playback, and analysis.

Documentation is sparse, see [javadocs](https://cdn.rawgit.com/processing/processing-sound/master/reference/processing/sound/package-summary.html) (using RawGit, not formally hosted anywere obvious)


There is a `SoundObject` *interface* which is extended by `Oscillator` and `Noise`

## ?


`Engine` x
`MethClaInterface` x


## Audio Synthesis

### Oscillators

`SawOsc` (Oscillator)
`SinOsc` (Oscillator)
`SqrOsc` (SoundObject, but why not Oscillator)
`TriOsc` (Oscillator)
`Pulse` (SoundObject, but why not Oscillator)


`Env` x - ATR (Attack Sustain Release) *envelope generator*.


## Audio Playback

`SoundFile` (SoundObject)


### Audio Input

`AudioIn` (SoundObject)


### Noise Generators

* `BrownNoise` (Noise)
* `PinkNoise` (Noise)
* `WhiteNoise` (Noise)


### Audio Processing

? `Mix` (SoundObject)

#### Filters

`Bandpass` (SoundObject)
`HighPass` (SoundObject)
`LowPass` (SoundObject)

#### Effects

* `Delay` (SoundObject)
* `Reverb` (SoundObject)


## Audio Analysis

`FFT`

`AudioDevice` configures sample rate and buffer size of the audio server. It may not be necessary generally, but according to the FFTSpectrum example the buffer size cannot be larger than the fft size so we probably should set it.


`Amplitude`


## Etc

* [Processing-Beat-Detection](https://github.com/kctess5/Processing-Beat-Detection) uses Minim


