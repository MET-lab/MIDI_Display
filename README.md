# MIDI_Display.pde
A visualizer for MIDI output devices in Processing 3.

## Download and Install

	1.	Install Processing 3 from processing.org
	2.	After installing, from the top menu in Processing 3, select Sketch > Import Library > Add Library and type 'MidiBus' in filter. Select the MidiBus library, then press install.
	3.	Be sure to install any other drivers you may need for your MIDI device.

## Getting Started

	-	The first time you run MIDI_display with your MIDI device connected, check the console to make sure the index number next to your device's name matches the value of the 'midi_device' variable under "Configuration Parameters". 
	-	Changing the 'desiredBPM' will change the rate at which the timing indicator will move. If you wish to exceed 140 bpm, lower the 'frame_multipler' down to 1. This will ensure the indicator will continue to move across the screen at the correct rate. If not, the indicator will move at a slower rate than the desired BPM due to limitations in the rate at which the draw() function can be called and the number objects that to be redrawn.
	-	The program only supports MIDI input from the white keys (C3 to C5) and 2 black keys.
	-	Press the SPACEBAR start and reset the indicator position.
	-	Press the letter 'R' or 'r' TWICE to clear the display and reset the indicator position.

## License

GPL3

## Author

###Tenell Rhodes, February 2016
