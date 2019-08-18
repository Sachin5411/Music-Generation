# Music-Generation
Project_Music_Generation
Music can be generated even with the help of artificial intelligence. The following model uses LSTM to train our model on music dataset. Further it generates its own music using some random seed.


Model
The model used is sequential

The last layer is ofcourse a Dense Layer with linear activation
>>Steps involved
Reading midi files using midi library functions.
Data preparation for feeding our model: Data_Preparation.ipynb does the same, by converting midi files in required numpy arrays.
Trainig the model on above dataset
Generating a song for random seed and saving it as midi file.
Results:
The machine was able to generate the music, although it does not sound as much good (nor too bad). But it might be possible that in near future, with the help of new innovations, machines can do so.
