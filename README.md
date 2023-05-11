# Music-Emotion-Recognition

This repository contains implementation of a music emotion recognition system, which attempts to identify the emotions conveyed by a piece of music based on its audio and lyrics features. Specifically, I used the Russell's circular emotion model, which is based on the concepts of arousal and valence, to classify the emotions conveyed by the music.

The PMEmo2019 dataset was used for this project, which contains both dynamic and static audio features. However, I chose to use only static audio features in my implementation. Several machine learning algorithms were experimented with for both audio and lyrics features in other implementations, but my approach was to combine the audio and lyrics features and train a Keras functional model. This model takes in both audio and lyrics features and outputs values for arousal and valence.

Preprocessed data is also provided in this repository, making it easier to replicate the experiment and avoid the need for additional preprocessing.

## Dataset

The PMEmo2019 dataset [1] contains audio files with corresponding annotations in terms of arousal and valence values. Arousal is a measure of the level of excitement or energy in the music, while valence is a measure of the positivity or negativity of the emotions conveyed by the music

## Usage

To use this repository, simply download the preprocessed data and run the model on the audio and lyrics features. The model takes in a set of audio and lyrics features and outputs arousal and valence values.

The preprocessed data is also provided in this repository, so you can skip the preprocessing step if you want to directly use the preprocessed data.
## Dependencies

The following dependencies are required to run this project:

  * Keras
  * Tensorflow
  * nltk
  * numpy
  * pandas
  * matplotlib
  * sklearn
    
 ## Contributing
 
 We welcome contributions to this project. If you want to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them with clear commit messages.
4. Push your changes to your forked repository.
5. Create a pull request with a clear description of your changes.

## Contact
If you have any questions or issues, please contact me at rishabhvyas472@gmail.com

## References
[1] PMEmo2019 dataset, https://github.com/HuiZhangDB/PMEmo
