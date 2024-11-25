A small collection of pureData 0.54.1 patches that I built to learn more about pureData. The initial idea is to use pureData to debug and visualize what [midiTracker](https://github.com/zuggamasta/midiTracker) can do.

# Patches
List of patches you can find in this repository.

## `midi_in.pd` - MIDI Input Visualisation
Two graphs showing the latest incomming midi notes with channels 1-16 from left to right and note from bottom to top. A second graph shows the velocities of the notes. Listens to the active midi device.

This patch is maninly to debug if all channels work in sync, and if all data is arriving

##  `midi_in_ez.pd` - Simple MIDI Input Visualisation 
Eight horizontal radios that display the current note in the chromatic scale. As this is my private collection of patches, this currently just shows the first eight channels as this is what [midiTracker](https://github.com/zuggamasta/midiTracker) uses by default.

This patch is meant for debugging musical notes, intervals and chords. Listens to the active midi device.
