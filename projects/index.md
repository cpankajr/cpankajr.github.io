---
layout: page
title: Projects
tags: [project, pankaj, chauhan, sfit]
modified: 2017-09-16T20:53:07.573882-04:00
comments: false
---

My interests broadly lie in the fields of Speech Processing, machine learning and Signal Processing.
I recently got interested in understanding emotion from speech by using machine learning tools.


### Projects

* **Harmony Search for Feature Selection in Speech Emotion Recognition**  
*Major Project, Ongoing*  
Guide: Asst. Prof. Kevin D'souza  
**Details:**  
Selecting significant features out of large dimensions of the original speech features is an integral part of accurate speech emotion recognition. In this project, we proposed an automatic speech emotion classification system based on a harmony search algorithm as a feature selection strategy. 
-First, an audio signal is divided into small frames of 20 ms and MFCC features are extracted from each frame to generate an original feature set. 
-We employed Harmony search to derive local feature subsets for each pair of emotions. Selected subsets and original sets evaluated based on 10 fold cross-validation accuracy. 
-Finally, each local feature subset is fed to corresponding one-against-one SVM classifier, and the majority voting method is used to classify each emotional recording. 
-Experiments are conducted on the EMODB and IITKGP-SEHSC databases, demonstrating that size of each subset reduced to 50% of the size of original feature set, however, the accuracy remained almost same as original ones.
[<button type="button" class="btn btn-info">PPT</button>](/reports/be-proj-present.pdf)
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/cpankajr/Harmony-Search-for-Feature-Selection-in-ASER)  

* **Speech Emotion Recognition using Dynamic Time Warping**  
*Mini Project II, Jan 2017 - Apr 2017*    
**Details:**  
The purpose of speech emotion recognition system is to automatically classify speaker's utterances into five emotional states such as disgust, boredom, sadness, neutral, and happiness.
- Designed and built a speech emotion recognition system using SAVEE database on MATLAB
- Developed a trained model for detecting emotion using DTW classifier
- Obtained accuracy of 68.57%  
[<button type="button" class="btn btn-info">Report</button>](/reports/Mini-Project-2.pdf)
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/cpankajr/Speech-Emotion-Recognition-using-DTW)  

* **Electronic Piano**  
*Mini Project I, July 2016 - Oct 2016*  
**Details:**  
Built a piano with variable tuning feature using IC 555 in Astable mode.
IC sends high/low-frequency signals to a piezo buzzer based on the value of resistance corresponding to the key/button
pressed by the user thus producing the sound of the note. 
- Introduced potentiometers to obtain custom octave frequencies.  
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/cpankajr/p1)  

* **Line Follower Robot**  
*National Robotic Championship Organized by ARK tech in association with IIT Madras, Mumbai, India*  
*Vision (Sept 2015)*    
**Details:**  
The Line follower robot is a mobile machine that can detect and follow the line drawn on the floor.
- Built a robust line follower robot for a National Robotic Championship held at IIT Bombay.
- Programmed Arduino to control motors of robot.  

-----
  

[Here](/projects/courses) is a list of all the courses I have taken during undergraduate studies.
