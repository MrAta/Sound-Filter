# NRD(Noise Reduction Filter) 
Implementation of some noise reduction filters both in cpu and gpu
#compile
##for running on CPU
`g++  -Wall -g serial.cpp wavfile.cpp -o serial -std=c++0x`
#usage
`./serial input.wav output.wav filter_number`
