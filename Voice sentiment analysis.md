# Voice Sentiment ANALYSIS

The project is used to identify the emotions in a human voice either male or female. Raw audio files can be recorded and feed to the model and
it will return the gender as well as the emotion associated in the voice. 

the contributors in this project
1. Hardik Choudhary(11710334) B.tech Computer Science Lovely Professional University,
2. Abhishek Kumar Gupta(11710423) B.tech Computer Science Lovely Professional University

__________________________________________________________________________________________
##DATASET.

the Dataset is used in the project is the RAVDEES .
RAVDESS is one of the more common dataset used for this excercise by others. It's well liked because of its quality of speakers,
recording and it has 24 actors of different genders. And there's more! You can get it in song format as well. There's something for
everyone and their research project.

THE original Data size is about 24 GB with more thean 100,0000  audio files. so we have taken the less data from # kaggle with size about
536MB with total raw audio files 1440 in the wav format. 

________________________________________________________________________________________________________________________________________
##Model Working
the model works by first extracting the features from 1440 raw audio datafiles,  then preprocessing the data so that the model predicts
accurate results and then later feeding the data onto the 1D Convulutional Layer, so that the classifier predicts correct results.


____________________________________________________________________________________________________________________________________________
##testing

for testing purpose we are recording a audio from youtube and then feeding it onto our model so that it predicts correct output. 
