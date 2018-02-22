Dani:


Fourier Transform over Finite fields using the concept of 'circle' 
as the roots of unity of a finite field to define a character that acts like complex exponential

gcc wav.c galois.c -o wav -O3 -funroll-loops 

You can Fourier the 8bit1chan.wav to 8bit1chan-fourier.wav and recover it to inverse8bit1chan.wav


This is how it has to be executed

arg1 fourier or inverse = {-f or -i}
arg2 Input.wav
arg2 Output.wav

Example inverse fourier:

$ ./wav -i Input.wav Output.wav


Eduardo Ruiz
