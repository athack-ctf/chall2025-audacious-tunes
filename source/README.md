# Building Your Challenge

The purpose of this directory is to provide a reproducible way of rebuilding your challenge.

1) Get a 24-bit color depth bmp file of your flag (AtHack_BMPImage.bmp) (24 bit necessary for arss software)
2) Download 'The ARSS' (https://arss.sourceforge.net/index.shtml) Audio synthesis software.
3) Start The ARSS in your terminal by entering ./arss
4) Select '3) Noise Synthesis' by inputting '3', enter the path to your .bmp flag as the input file ('./AtHack_BMPImage.bmp') and any name you want with .wav (flag.wav) extension for the output.
5) Default options can be used as you follow the rest of the instructions, but I recommend raising the minimum frequency a little bit to rise above the noise of the audio file we will merge with later on
6) Insert the flag.wav and any other audio (AudioPlaceholder.mp3) file of your choice into audacity and save the project as a .wav file.

You are now done, the final wav file will appear to be the audio file (AudioPlaceholder.mp3) when played, but will contain the bmp when viewed as a spectogram.

