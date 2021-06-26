# Single-Speaker-TTS

Text to Speech Synthesis using Speaker Adaptation:-

●  Based on a neural network-based system for text-to-speech (TTS) synthesis that is able to generate speech audio in the voice of different speakers, including those unseen during training. Original code was taken from different commits in the https://github.com/CorentinJ/Real-Time-Voice-Cloning/tree/054f16ecc186d8d4fa280a890a67418e6b9667a8

●  System consists of three independently trained components: (1) a speaker encoder network to generate a fixed-dimensional embedding vector; (2) a sequence-to-sequence synthesis network based on Tacotron 2, which generates a mel spectrogram from text, conditioned on the speaker embedding; (3) an auto-regressive WaveNet-based vocoder that converts the mel spectrogram into a sequence of time domain waveform samples.

●  Adapted for a single speaker dataset by fine-tuning the synthesizer on 8 mins of data.

●  Mean Opinion Score of 3.9/5 was achieved. The adapted models the prosody information of the single speaker more accurately than the multi-speaker TTS, and this is reflected in the MOS and other evaluative tests.

Recorded Data: https://drive.google.com/drive/folders/1ewKtJPIZlcUdKB-y4qPUBMlIZNKcYhTZ?usp=sharing

![alt text](https://https://github.com/shwetha0312/Single-Speaker-TTS/blob/main/predicted_Spectrogram.png?raw=true)

 
