# Speech-Emotion-Recognition

**INTRODUCTION:** 

This project is about recognizing a person’s emotion from his/her voice, our program is capable of **recognizing both male as well as female** voices, and can recognize **8 different emotional states**. 

**MOTIVATION:** 

The global voice assistant market size was valued at **USD 2.48 billion** in 2020 and is expected to **grow at a CAGR of 32.7%**. This shows the increased amount of Human- Machine interaction through voice, but still many of the voice assistants lack “emotional recognition”, we hope that our project can get AI a step closer in understanding our emotions. 

**DATASET:** 

Ryerson Audio-Visual Database of Emotional Speech and Song.The audio files are in the WAV format and have a sampling rate of 48 kHz and a bit depth of 16 bits. The dataset also includes metadata such as the gender and age of the actors, the emotion expressed, and the intensity of the emotion.

**ALGORITHMS / ARCHITECTURES:** 

Two parallel convolutional neural networks (CNN) in parallel with a Transformer encoder network. 


![Aspose Words a77f579c-c4e0-4385-a44c-1fde6deb29d9 001](https://github.com/tanmay154agrawal/Speech-Emotion-Recognition/assets/124059983/cc522a44-6edf-4876-aa0f-b25d94b6ee1a)

Feature used for training is MFCC(Mel Frequency Cepstral Coefficients) . Mel Spectrograms are used in calculating MFCCs, which are a higher-level representation of pitch transition 


![Aspose Words a77f579c-c4e0-4385-a44c-1fde6deb29d9 002](https://github.com/tanmay154agrawal/Speech-Emotion-Recognition/assets/124059983/2dcc6aa5-a1bd-4d1b-ae3a-301c5a064bae)

Since , our model was highly parameterised it was prone to overfitting. To overcome this we used augmentation. 

Augmentation techniques used: 

Random Noise 

Stretch 

Gaussian Noise  

**Results:** 


![Aspose Words a77f579c-c4e0-4385-a44c-1fde6deb29d9 003](https://github.com/tanmay154agrawal/Speech-Emotion-Recognition/assets/124059983/5e39ff3a-5f75-46b2-9e5b-3f9ae55ec9bc)

Testing accuracy : 51% 



