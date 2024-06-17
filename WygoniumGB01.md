# Wygonium GB01 Synth

![A picture of the Wygonium GB01 Synthesizer. It is a wedge-shaped device that is mostly black with a white front panel. It has a display screen and knobs.](/images/Wygonium_GB01_square.jpg)

## Info

- 6 oscillators each with 7 waveforms (from pristine classics to lo-fi vintage digital synths)
    - 2 primary oscillators with independent adjustment ±12 semitones 
    - 4 “subharmonic” oscillators with selectable divisions (1-24) of the played pitch
    - Global detune for huge sounds
- Noise generator
- 4 independent parallel resonant bandpass filters with LFO modulation
- Adjustable LFO with 6 waveforms and touch restart
- Effects:
    - Drive, from subtle warmth to harsh overtones
    - Atmospheric stereo plate reverb
    - Lush stereo chorus
    - Looping digital delay with in/out for overdubs
- Flexible mixing stages
- Selectable velocity curves
- Pitch quantization
- Latched sustain
- One-shot or looping envelope
- Preset storage
- Pitch input quantization to musical scales, with root note setting

## Details

![Another picture of the GB01, showing the front panel](/images/GB01_front.png)

![Another picture of the GB01, showing the rear panel](/images/GB01_back.png)

#### Hardware 

- Teensy 4.1
- Teensy Audio Board
- 2.42" OLED display (SSD1309)
- 4x Bourns rotary encoders
- 1x 10k audio taper potentiometer
- 8x NKK 12mm tactile buttons
- Jacks:
    - 2x 1/4" audio
    - 1x 1/8" headphones
    - 1x 2.1 DC power
- 1x Power switch
- 1x RJ45 Ethernet jack
- Custom circuit boards
- 2x CD4051 (for encoders)
- 1x 74HC165 (for buttons)
- Miscellaneous passives

#### Software

- The usual, standard Teensy/Arduino libraries
- Additional Teensy audio libraries (most slightly modified to get specific parameters):
    - Ensemble by Alexander Davis/[Vince R. Pearson (ElectroTechnique)](https://github.com/ElectroTechnique/TSynth-Teensy4.1) 
    - Plate Reverb by [Piotr Zapart (hexefx)](https://github.com/hexeguitar/hexefx_audiolib_F32)
    - Delay10Tap [from Teensy forum user HOUTSON](https://forum.pjrc.com/index.php?threads/can-i-modulate-the-delay-time.61513/post-265954)
- Custom Teensy audio libraries
    - Analysis to Variable to track LFO
    - Added restart() method to Waveform class to retrigger when used as LFO
- 12AX7 Tube response curve [from Teensy forum user HOUTSON](https://forum.pjrc.com/index.php?threads/teensy-based-multistage-distortion-modeling-pedal.44061/post-229555)
- Three waveforms used from [Adventure Kid Waveforms (AKWF)](https://github.com/KristofferKarlAxelEkstrand/AKWF-FREE)