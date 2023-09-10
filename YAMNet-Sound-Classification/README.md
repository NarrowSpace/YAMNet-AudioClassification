# YAMNet-EnvironmentalSoundClassification

![ezgif-5-4244f3f8f3](https://github.com/NarrowSpace/Environmental-Sound-Classification/assets/105491905/481d8225-43c4-4e97-8840-e0c76ef16329)


This project uses the microphone of your computer as input and classifies the audio captured by this microphone using the YAMNet Model, which can be downloaded from Tensorflow Hub: https://tfhub.dev/google/lite-model/yamnet/tflite/1. 

Additionally, you will need to download the CSV file from their GitHub repository: https://github.com/tensorflow/models/blob/master/research/audioset/yamnet/yamnet_class_map.csv. 

(This repository already contains these files.)

Users can press the start button to begin recording and analyzing the audio captured from the microphone in real-time. The top 3 results will be displayed in the text box. Press the stop button to finish the recording and analysis.

Troubleshooting: Even though the model claims that it can recognize 522 types of sounds (refers to the CSV file), the accuracy was found to be quite low after testing. For instance, the piano and drum sounds in the video, despite being listed, could not be accurately identified.

The list of required libraries to install is as follows:
1. Customtkinter
2. TensorFlow
3. Pyaudio

python version: 3.10
