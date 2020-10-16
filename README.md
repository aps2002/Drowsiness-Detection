# Drowsiness-Detection
Uses live feed video from the webcam to monitor the users eyes. If the eyes are closed for a significant amount of time, a loud alarm noise will be played to wake them up. Useful for truck drivers or staying up to study. 

Usages:

No alarm:
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat

With alarm
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav


the alarm sound can be changed by adding a different alarm.wav
