# bot-gragas league python project
 

This is my object detection project based on Tensorflow. My goal was to create a League of Legends bot that would automatically recognize characters on the screen and perform voice commands given by the player. The bot is meant to play support champion - Yuumi.

### Technologies:
   - [Python 3.10](https://www.python.org/)
   - [Tensorflow 2.10](https://www.tensorflow.org/)
   - [OpenCV](https://opencv.org/)
   - [MSS](https://python-mss.readthedocs.io/)
   - [AutoHotKey](https://pypi.org/project/ahk/)
   - [Numpy](https://numpy.org/)
   - [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)

Simple guide how to use it:
1. To interact with the program, press the Left Control button
2. After hearing "beep" sound say command (bot listens for 2 seconds)
3. The finish of recording is again notified by sound signal
4. To quit program press "P" button

Command list (only in Polish):
- strzel + (champion name) - Yuumi casts PROWLING PROJECTILE in the enemy direction
- skocz + (champion name) - Yuumi jumps on the pointed ally
- lecz + (champion name) - Yuumi heals the ally which she sits on
- super + (champion name) - Yuumi casts FINAL CHAPTER in enemy direction
- podpal + (champion name) - Yuumi ignites enemy
- zwolnij + (champion name) - Yuumi uses an exhaust spell on the enemy
- kup + (item name) - Yuumi buys the given item
- cofnij + (item name) - Yuumi undoes the purchase
 

Important note
League of Legends client has to be opened in the top left corner, in 1280x720 resolution, windowed! Currently bot is trained for Gragas and Nunu recognition. You can check how it works here.

 

Sample recognition
 

## Gragas

gragas recognition from google images

 ![gragas recognition from google images](./img/gragas.jpg)

## Nunu and Willump

nunu recognition from google images

![nunu recognition from google images](./img/nunu.jpg)
