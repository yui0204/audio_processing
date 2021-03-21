
#  Audio signal provessing tool

This repository contains audio signal processing tools

# Usage

guitar = WavfileOperate("./Acoustic_guitar181.wav").wavedata

guitar.plot()
guitar.stft_plot()
guitar.melspectrogram(plot=True)
guitar.mfcc(plot=True)

# Requirements
python

numpy
pandas
librosa
scipy
sklearn
matplotlib