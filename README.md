# ДП-5В

The DP-5V is a MIDI device that generates MIDI signals from radiation using an internal Geiger counter.

## Features

### Quantization

Notes can be quantized to whole note, half note, quarter note, eighth note all the way up to 128th notes. When the Geiger Counter receives a signal, it waits in a buffer until the note can be triggered.

### BPM

Only used when quantized is enabled, ranges from 40bpm to 250bpm.

### Modulo Gate

When the modulo gate is set to 2, every second signal is a note off of the previous signal. When the modulo gate is set to 1, every signal acts as both a note off for the previous note, and a note on for the current note.
