<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Simple monophonic synth with PWM output: 5 inputs, 8 switches to choose sounds/notes, left/right output channels

## How to test

Connect inputs 0:4 to the output of 5 IR sensors, the 8 inout pins to 8 switches and the at least one of the outputs (left or right) to a low pass filter (I suggest a Sallen-Key configuration). Remove the DC at the output with an RC high pass filter and connect to a speaker.

## External hardware

5 IR modules to generate notes, 8 switches to choose sounds/notes, two low-pass filters to generate left/right audio signals (better if 2nd order filters), two high pass filters left/right to remove the DC before going to the speaker.
