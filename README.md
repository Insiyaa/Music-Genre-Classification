# Music Genre Classification
## Beginning
This project started as a mini team project with an aim to learn different machine learning models. The initial problem statement was to classify music into any two categories. Different features like tempo, beats, stft, mfccs, etc were extracted using [Librosa]('https://librosa.github.io/') from the [GTZAN Genre Collection]('http://marsyasweb.appspot.com/download/data_sets/') dataset. On that data we implemented logistic regression and neural network from scratch independent of any framework.
The repository for this task is [here]('https://github.com/Insiyaa/Music-Tagging').

## What next?
After this project, I went on learning more about computer vision and deep learning. Reading more and more about it, I started thinking if I could apply CNNs on the music data. Also I hoped that transfer learning would help me attain accuracy closer to the [State of the art models]('https://musicinformationretrieval.wordpress.com/2017/02/06/state-of-the-art-audio-tag-classification-genre/') on GTZAN dataset.

## Representing Music as Image
A very naive idea of mine was to simply plot the y values as shown below.
[Pop Waveform]("http://i68.tinypic.com/6eg8lc.png")
By soon I realized that it won't just work as it doesn't give much information. While going through different articles to for visualizing music, I came across this [paper]('cs231n.stanford.edu/reports/2017/pdfs/22.pdf') (luckily having the same idea as mine) and decided to go for melspectograms.
A spectrogram is a visual representation of the spectrum of frequencies of sound or other signal as they vary with time. Spectograms allow looking at the whole song once and get the information about the tones present right away!
[img], [img]
## Transfer Learning
While exploring more and more about deep learning, I came across PyTorch and decided to use it. But later on I started with [Practical Deep Learning for Coders, v3]('https://course-v3.fast.ai/') and decided to use fastai library which is easier to use, intuitive, reliable and build on the top of PyTorch.
I implemented the pretrained models of ResNet34 and ResNet50 using Google Colab.













