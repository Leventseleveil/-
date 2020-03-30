# music_retrieve_code description
A music retrieve  code description in Python

### 0. Setup Environment
In order to run successfully, it is best to install Anaconda and run the code under the Anaconda Prompt command window. And this project is running in Python3.x, and please enusre following packages are installed:
- librosa
- pyaudio
- wave
- numpy
- dtw

### 1. How to run

(1) Put the music library in folder `music_base`, during which the algorithm will recognize the playing music and output a similiar music, the supported format is `.wav`.

And we have put some songs in music folder `music_base`.

(2) Run script `librosa_music.py`, a music retrieve database is created and stored as `beatDatabase.npy`.

(3) Run script `librosa_main.py`, choose the song to play, then the system will retrieve matched song and react accordingly.

(4) We have put some songs in `music_test` to test. All you should do is run script `librosa_main.py`, then the reaction will be done. And we made the list `Music-Reaction.txt` to show corresponding reaction to the song.

### 2. beat.py

In this code, we can analyze the time series of rhythm points and their time-frequency characteristics of a song as it changes with time.



