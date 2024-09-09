This is a Text to Speech converter for the SpeakJet speech chip.
It is very Alpha and I'm sure contains bugs and mistakes.

Designed for the Altair-Duino over Serial port 

64kb required. Best use on a Harddrive but will work off Floppy Disk if you have the Disk Controller card.
CP/M 2.2. serial port SIO2 PORT 2

JSAY.COM is the main program you run and enter either a word or a line of text to convert.

The converted phonics are saved in TEXTJET.TXT then output through JETSAY.COM

JETSAY.COM Will read converted phonics text inside the TEXTTEMP.TXT file

TEXTJET.TXT is a temp file that is erased and recreated when JSAY.COM is run.

you can copy TEXTJET.TXT to another file and save the contents which you can use inside of 
your own program where you want to use speech or you can replay them through JETSAY.COM in the future
by copying the file name back to TEXTJET.TXT

the rest of the included files in the LIBRARY Archive are needed to support JSAY. 
BRUN is needed to run all the programs.

JETTEXT will play any saved Text to Speech converted file. you can even include Escape code effects.

JETDEMO.TXT is a short demo you can playback with JETTEXT.COM

Update: 09/05/2024
