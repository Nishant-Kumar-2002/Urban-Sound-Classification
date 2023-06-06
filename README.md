# Urban-Sound-Classification

This project is a sound Classification problem.

Dataset Used - Urban Sound 8k

Link to dataset :- https://urbansounddataset.weebly.com/urbansound8k.html

This dataset is given in 10 folds and we have to use 10-Fold Cross Validation.

To install all the libraries to run the execute the ipynb file.

pip install -r requirements.txt

Librosa is a library used here for processing sound.

Librosa has many features to extract, here we use two features 
i.e mfcc and mel spectrogram that are widely used.

Using MFCC(Mel Frequency Cepstral Co-efficients) and ANN to classify the sound.

It gives a decent accuracy but not a par score.

Using Mel Spectrogram and CNN to classify the sound.

A spectrogram is a visual representation of the spectrum of frequencies of sound or other signal as they vary with time.

Different sound have differnt mel spectrogram and we use this as an image to classify sound using CNN.

It is most effective way of sound classification. It produces way better results than mfcc.

Link to my notebook below :- 

https://www.kaggle.com/code/nishantkumar21092002/urban-sound-classification

Thank You.
