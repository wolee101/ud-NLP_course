README.md - NLP projects


## **Project Title**

NLP projects (Udacity Natural Language Processing Course projects)


## **Description**

The goal of this course is to learn cutting-edge natural language processing techniques to process speech and analyze text. The course included popular Natural Language Processing (NLP) applications such as sentiment analysis and topic modeling, as well as included projects that use probabilistic and deep learning models. With some template code provided, I implemented additional functionality to successfully complete the projects. The three core projects of this course are listed below:

1. [Part of speech tagger](./1_HMM_tagger/readme.md)

A hidden Markov model (HMM) for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf) was built using the [Pomegranate](https://github.com/jmschrei/pomegranate) library. A Most Frequent Class (MFC) tagger was built and used as a baseline to estimate the frequency of tags and words in the training corpus. When the model was evaluated, the test set accuracy was 96%.


2. [Machine translator](./2_Machine_translator/readme.md)

A deep neural network was built that functions as part of an end-to-end machine translation pipeline. It generates French translation from English text input. Word embedding and several deep learning models were explored in the training. Keras was used and different neural network architectures were tested.


3. [Speech recognizer](./3_DNN_speech_recognizer/readme.md)  

A deep neural network was built that functions as part of an end-to-end automatic speech recognition (ASR) pipeline. After building several neural networks that mapped audio features to transcribed text, the final model used a combination of a convolutional neural network and bi-directional recurrent neural networks. The model converted raw audio input into feature representations and then into transcribed text. Keras was used again.


## **Datasets:**

Below are the datasets used for each project listed above.

1. A copy of the[ Brown corpus](https://en.wikipedia.org/wiki/Brown_Corpus) (originally from the NLTK library) that has already been pre-processed to only include the [universal tagset](https://arxiv.org/pdf/1104.2086.pdf)
2. A dataset created by Udacity that included small vocabulary for fast training
3. [LibriSpeech dataset](http://www.openslr.org/12/)
