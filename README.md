# Automative-Morrocan-Arabic-Speech-Command-Datset
In this repository, you will find the dataset used for building the first automotive speech recognition system in the Arabic dialect, specifically the Moroccan dialect. The dataset includes 20 commonly used in-car commands, carefully selected to aid Arabic drivers in making their driving experience comfortable and safe by reducing the distraction ratio.

## Dataset Description

The automative Morrocan Arabic Speech Commad Datset (MASCD) dataset was created to develop a robust Speech Recognition system capable of recognizing in-car voice commands in the Moroccan Arabic language. 
The final dataset is in form of (X,Y)  where X is the audio (input) and Y is the label of the audio. The datset consists of 20 commad classes with 2800 labeled audios, each audio file is around two seconds in length, contains a single command, sampled at 16 kHz, 16 bit per sample, and in mono channel. To ensure dataset robustness, 25% of audio were recrded in noisy condition (cars, roads, Trafic noise) and 75% are recorded in clean environmemnts. 
Each command was recorded 10 times by 14 contributors. Consequently, we have a total of 140 audio files for each command, resulting in 2800 audio files in total (14 contributors x 10 repetitions x 20 commands = 2800).
The dataset size is ~180 MB.

## Dataset Structure
The built datset is presented in the dataset file in the repesotory. 
there are 14 file, each one contain the recording of each  contributors.    
each contributors file contain 10 sub-file which contain recording of each command 10 times. 
dataset file

Dataset file structure: 
  -> contributor-1 \n
     -> Command-1
         -> Command-1 Repetition-1
         ..
         -> Command-1 Repetition-10
    ...
    -> Command-20
         -> Command-20 Repetition-1
         ..
         -> Command-20 Repetition-10
  ...
  -> contributor-14


    


#Note :
The dataset used in this research is currently in use and not publicly available. 
However, authors interested in utilizing this dataset or our codes for research purposes are welcome to do so. 
Please send an email to my official account, and I will gladly provide you with access to these resources.

my email : soufiyane.ouali@usmba.ac.ma
