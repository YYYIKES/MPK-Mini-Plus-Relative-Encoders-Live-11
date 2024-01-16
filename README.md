# Akai MPK Mini Plus Remote Script and whatnot for Ableton Live 11

Just my personal, non-python, slightly-modified Ableton Live 11 remote script for the Akai MPK Mini Plus. 

What this is for:
- Enabling relative encoders
- Allowing macro bank switching via the FF/RW buttons to utilize all 16 macro knobs on rack devices, etc. (I just realized one could probably make more banks to control more than 16 parameters in instruments/FX plug-ins)
- Toggling between different knob speeds (Optional. Requires MidiPipe) The knob action is pretty slow by default so I made a few Pipes to toggle different modes to suit various knob curve preferences.

Usage:
- Using the Akai Professional MPK mini Plus Program Editor, change each knob from "Absolute" to "Relative". Alternatively, open the .mpkminiplus program in the editor, change any other settings you desire, and send it to the controller. Make sure you backup your custom programs before sending this one to your unit
- Put the "MPK Mini Plus Relative Encoders" folder into Users/[username]/Library/Ableton/[Current Live Version]/User Remote Scripts/ (Note: Don't rename UserConfiguration.txt)
- In Ableton Live, open Preferences (cmd + ,) and go to the MIDI tab. Select "MPK Mini Plus Relative Encoders" for the control surface. Select "MidiPipe Output 1" for the Input, and "MidiPipe Input 1" for the output. (These might be different depending on your MidiPipe setup). Enable "Track" for MPK Mini Plus Relative Encoders input and output, and whatever your sync options are.
- Put the MidiPipe .mipi files wherever you like. I also added them to my Dock so I can toggle them on the fly, and added the "Normal" one to my login items.

I think that's it.
