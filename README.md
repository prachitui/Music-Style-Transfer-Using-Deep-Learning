# Music Style Transfer using Deep Learning
This project implements a music style transferapplication that blends the structure of one audio piece with the stylistic characteristics of another using Convolutional Neural Networks 
(CNNs). The goal is to generate novel audio outputs that maintain the original melody while incorporating stylistic traits from a target genre.

## Overview

- **Content Audio**: Classical music piece
- **Style Audio**: Jazz music piece
- **Dataset Used**: GTZAN dataset

## Noebook Functions

- **`load_audio`**: For loading audio files.
- **`audio_to_spectrogram`**: Converts audio files to spectrograms for analysis.
- **`style_transfer`**: Contains the CNN model and the style transfer algorithm.
- **`plot_spectrogram`**: Functions to visualize audio spectrograms.


## Parameters
- **'Content Weight:'** Controls the influence of the content audio (default: 1).
- **'Style Weight:'** Controls the influence of the style audio (default: 1e5).
  
Adjust these weights in the style_transfer function to achieve different balances between content preservation and style transfer.

## Result
The project successfully demonstrates the ability to generate new audio compositions that preserve the original melody while incorporating stylistic elements from jazz music. You can listen
to the generated output (output.wav) under the output folder.
