# Drowsiness-Detector
Using webcam, it detects if the person gets drowsy or feels sleepy.
It uses shape_predictor '.dat' file and an audio file as argument if the script is run through command line.
A threshold value is set as 0.3 which is the 'eye aspect ratio'.
If Eye aspect ratio remains below 0.3 for 48 consecutive frames it alerts the person by enabling the alarm 
