# Gesture-Recognition


Smart TV comes up with the some additional feature like gesture recognition. Every hand gestures says something, for e.g. if I will swap the hand on left it could mean 
that I want to change the jump backward by 10 seconds and so on.

In this Problem statement we have to identify the 5 hands movement as followed:

* Thumbs up:  Increase the volume
* Thumbs down: Decrease the volume
* Left swipe: Jump backwards 10 seconds
* Right swipe: Jump forward 10 seconds  
* Stop: Pause the movie


I have tried two approach for same. 

1) using 3D convolution network
2) Sequence model with Convolution

Since each images(taken from video) has related to the its sequence in the next/previous image. It will be trained either with 3D convolution or Convolution + Sequence model(GRU in my case)
