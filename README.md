# Mood Radio

## Overview
In this work, we have created a system which recommends songs to people based on their mood. The system is divided into two parts.  
First, the emotions or mood of the person is recognized from the facial expressions. For that, a deep learning model is trained on FER2013 dataset of Microsoft. For now, the model is trained to predict only 3 emotions i.e. Happy, Angry, and Sad.  
Second, a dataset of songs is created and the mood of the songs is predicted using the lyrics and the audio features. For that, a bimodal deep learning approach is used. This model is trained on Million Songs Dataset.
