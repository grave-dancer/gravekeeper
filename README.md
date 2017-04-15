# openphreak

OpenPhreak is the software used by GraveStone10, a hardware device. 

https://github.com/grave-dancer/gravestone/

OpenPhreak is written in C++ for the MSP430FR59XX series MCU's.
I decided to have a seperate repository for it besides the GraveStone repository.

Software Features:
Embedded Audio Cryptography: Provides fast AES-256 encryption of audio streams.
Embedded Audio Steganography: Provides fast FFT based Audio "Hacking" for data hiding.
Embedded Audio/Voice Augmentation: Provides fast transformation and filtering of audio streams.
Embedded Audio Capture/Playback: Can save and play back recorded audio.

The term "phreaking" comes from the idea that this is meant to be used with telephony.
OpenPhreak allows you to easily perform encryption + steganography on any cell phone that supports TRRS jack headphones.

This, in effect, hides your conversations from surveillance, and possible wiretapping.

The idea is to allow you to make encrypted phone calls without revealing that you're using encryption.
