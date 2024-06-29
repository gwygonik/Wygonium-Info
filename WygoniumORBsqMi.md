[<img alt="Return to main page link image" src="images/nav_main.png" height="50px">](/README.md)

# Wygonium ORBsq Mi MIDI Algorithmic Sequencer

![A picture of the Wygonium ORBsq Mi MIDI sequencer. It is a wedge-shaped device that is entirely black. It has a display screen and several sliders for input.](/images/Wygonium_ORBsqMi_square.jpg)

## Info

- Orbital path through a deterministic multi-dimensional noise field
- Variable-speed drifting creates ever-evolving patterns
- Scale and Root Note settings for always in-key sequences
- Adjustable step count from 2-16 for polyrhythmic sequences
- Selectable step durations in tempo-based note lengths
- Algorithmic filtering of steps:
    - Two-dimensional noise +/-
    - Euclidean
- MIDI features:
    - Selectable MIDI channels for unfiltered and filtered notes
    - Selectable MIDI channel for drone note
    - Drone configurable for root note or drifting first note
    - MIDI clock / start / stop output

## Demo Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/c1_hUcucz6w?si=nXC1HzyZE3YY0hJB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Details

#### Hardware 

- Teensy 4.1
- 2.42" OLED display
- 3x Bourns 30mm 10K illuminated sliders
- 2x Bourns 30mm 10K illuminated sliders with center detent
- 1x Omron Electronics tactile switch
- 1x I2C rotary encoder
- Jacks:
    - 1x DIN5-180 (MIDI)
    - 1x 2.1mm DC power
- 1x Power switch
- 1x 5V power regulator
- Several custom PCBs
- Various passives

#### Software

- Standard Arduino/Teensy libraries
- FastLED implementation of Perlin Noise

__________

<table align="center">
    <tr valign="top">
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/"><img src="images/WygoniumKit_square.png" width="100px" /></a><p><h4 id="wygonium-intro"><a href="/Wygonium-Info/">Wygonium Intro</a></h4></p></td>
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/WygoniumGB01.html"><img src="images/Wygonium_GB01_square.jpg" width="100px" /></a><p><h4 id="gb01-synth"><a href="/Wygonium-Info/WygoniumGB01.html">GB01 Synth</a></h4></p></td>
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/CRBController.html"><img src="images/Wygonium_CRB_square.jpg" width="100px" /></a><p><h4 id="crb-ribbon-controller"><a href="/Wygonium-Info/CRBController.html">C|RB Ribbon Controller</a></h4></p></td>
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/WygoniumM101.html"><img src="images/Wygonium_M101_square.jpg" width="100px" /></a><p><h4 id="m101-midi-input"><a href="/Wygonium-Info/WygoniumM101.html">M101 MIDI Input</a></h4></p></td>
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/WygoniumORBsq.html"><img src="images/Wygonium_ORBsq_square.jpg" width="100px" /></a><p><h4 id="orbsq-algorithmic-sequencer"><a href="/Wygonium-Info/WygoniumORBsq.html">ORBsq Algorithmic Sequencer</a></h4></p></td>
        <td align="center" width="150px" valign="top"><a href="/Wygonium-Info/WygoniumORBsqMi.html"><img src="images/Wygonium_ORBsqMi_square.jpg" width="100px" /></a><p><h4 id="orbsqmi-midi-algorithmic-sequencer"><a href="/Wygonium-Info/WygoniumORBsqMi.html">ORBsq Mi MIDI Sequencer</a></h4></p></td>
    </tr>
</table>
