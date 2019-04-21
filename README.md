# Music Generation
This project aims to build and train a neural network to generate music files or Piano tunes.

## Requirements

* Python 3.x
* Installing the following packages using pip:
	* Music21
	* Keras
	* Tensorflow
	* h5py

## Training

To train the network run **lstm.py**.

E.g.

```
python lstm.py
```

The network will use midi file in ./midi_songs to train the network. The midi files only contain a single instrument to get the most out of the training.


## Generating music

Once you have trained the network you can generate text using **predict.py**

E.g.

```
python predict.py
```

This will generate a **test_output** file, this file will be of **.mid** format

## MIDI files (.mid)
 .MID or .MIDI file extension are Musical Instrument Digital Interface file.

Unlike regular audio files like MP3 or WAV files, MIDI files don't contain actual audio data and are therefore much smaller in size. MID file can explain what notes are played, when they're played, and how long or loud each note should be.

Files in this format are basically instructional files that explain how the sound should be produced once attached to a playback device or loaded into a particular software program that knows how to interpret the data.

**To play and listen to output of these file, use Windows Media Player**