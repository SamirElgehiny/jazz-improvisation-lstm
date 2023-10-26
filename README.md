# Jazz Improvisation with LSTM

This repository contains an implementation of an LSTM network for generating jazz solos. The model is trained on a corpus of jazz music.

## Approach

The model is a recurrent neural network (RNN) with a single hidden layer of 128 units. The RNN is trained using the Adam optimizer and the cross-entropy loss function.

The model is trained to generate sequences of musical values, which can then be converted to MIDI notes. The model learns the statistical relationships between musical values and can use this knowledge to generate new solos that are both creative and musically correct.

## Results

The model is capable of generating jazz solos that sound like they were played by a human musician.


## Usage

To use the model, simply generate a random seed musical value and feed it to the model. The model will then generate a sequence of musical values until it reaches a stop value.

You can use the model to generate jazz solos for various purposes, such as creating backing tracks for other instruments, composing jazz pieces, or simply for fun.

Feel free to clone the repository and experiment with generating your own jazz solos!


