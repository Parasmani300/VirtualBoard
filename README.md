# VirtualBoard
This is a short project on computer vision through which I am making a virtual marker which would write on the screen as per gesture provided by the hand using opencv in python

# Description 
We will be doing this project in two steps:
Step 1:
In the first step we will find the HSV value so that we only detect the gesture of the object of interest and remove un neccsery noise.

# Notice :-> For better hsv value keep in the mind to keep the marker/pen to be used of same color throughout and if possible avoid using the marker/pen of the same color as of 
  the environment for better result.
  
  `pip install -r requirements.txt`
  
  `python finding_hsv_values.py`
  
  Once done setting up the hsv values. Press "S" to save the value for future use.
  
Step 2: 
In this step we will get the desired output i.e the virtual pen in action. 

`python virtualboard.py`

To clear the board press "C"
