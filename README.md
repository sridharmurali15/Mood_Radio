# Mood Radio

## Overview
In this work, we have created a system which recommends songs to people based on their mood. The system is divided into two parts.  
First, the emotions or mood of the person is recognized from the facial expressions. For that, a deep learning model is trained on FER2013 dataset of Microsoft. For now, the model is trained to predict only 3 emotions i.e. Happy, Angry, and Sad.  
Second, a dataset of songs is created and the mood of the songs is predicted using the audio features. For that, we have used the Spotify API of python to find the audio features of the song and then we trained a model to predict emotion of the song. For now, the model is trained to predict only 4 emotions i.e. Calm, Energetic, Happy, Sad.
