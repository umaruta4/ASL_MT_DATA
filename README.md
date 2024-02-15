# SL Motion Translator Client Data

This is the list of sign language data collected using motion translator client

feel free to contribute to dataset

Motion Translator Client link : https://github.com/umaruta4/MotionTranslatorClient


# Field explanation

"requests" => This contains all the SL dataset recorded

"table" => This explains what type of data is being recorded

"classValue" => This is the label of the data

"text" => This is the text meaning of the data

"data" => This contains the controllers data which is _leftControllerRecordData and _rightControllerRecordData


# Explanation of the controller values :

Each controller (right and left) contains 14 different channels.

This is the channel and the explanation

1 => Trigger Touch (boolean)

2 => Trigger Press (boolean)

3 => Grip (float)

4 => Thumb Touch (boolean

5 => Controller X Position (float)

6 => Controller Y Position (float)

7 => Controller Z Position (float)

8 => Controller X Velocity (float)

9 => Controller Y Velocity (float)

10 => Controller Z Velocity (float)

11 => Controller W Quaternion (float)

12 => Controller X Quaternion (float)

13 => Controller Y Quaternion (float)

14 => Controller Z Quaternion (float)


And this all recorded over time.
