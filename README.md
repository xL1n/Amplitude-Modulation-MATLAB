# Amplitude_modulation_MATLAB
This is a amplitude modulation code i write in Year 2 of my BEng EEE study 

The "BER_function" is MATLAB function which calculate the BER for random number of N bits signal, the code include the process of modulating the binary signal onto COS carrier wave and transmit through AWGN channel, then demodulate, and pass through LP filter to remove the extra frequency components caused by demodulation process, finally convert the filtered signal back to binary signal and compare with input signal in order to find the error hence BER 

"AM_SNR_4" file is based on the first "BER_function" files. This file simulates the binary signal transmission process with SNR = 4 through AWGN channel. This file will show 2 graphs, one is time domain signals, another one is frequency domain signals (of binary signal at some stage during this modem process)
