# ДП-5В

The DP-5V (ДП-5В) is a MIDI device that generates MIDI signals from radiation using an internal geiger counter. It is named after the famous Soviet geiger counter used by Chernobyl liquidators in 1986.

## Features

The DP-5V has 3 main settings.

### Quantization

When turned on, notes can be quantized to whole note, half note, quarter note, eighth note all the way up to 128th notes. When the Geiger Counter receives a signal, it waits in a buffer until the note can be triggered.

### BPM

When in automatic mode, the BPM is based on the amount of clicks per minute with a default setting of 60 BPM. When in automatic mode, the BPM can be set from 40bpm to 500bpm.

### Modulo Gate

When the modulo gate is set to 2, every second signal is a note off of the previous signal. When the modulo gate is set to 1, every signal acts as both a note off for the previous note, and a note on for the current note.

![DP-5V](https://cdn.githubraw.com/struct78/DP-5V/main/images/DP-5V.png)
