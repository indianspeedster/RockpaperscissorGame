### Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

##### pip install requirements.txt

### Description
Rock–paper–scissors (also known as scissors-paper-rock or other variants) is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V). "Scissors" is identical to the two-fingered V sign (aka "victory" or "peace sign") except that it is pointed horizontally instead of being held upright in the air. A simultaneous, zero-sum game, it has only two possible outcomes: a draw, or a win for one player and a loss for the other.

### Rules
##### Scissors cuts Paper --> Paper covers Rock --> Rock crushes Scissors 
<img src="https://camo.githubusercontent.com/e98e619b39936b20a7bd7844a40607fce76a469d/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f362f36372f526f636b2d70617065722d73636973736f72732e737667">


### Functionalities
1) Filters to detect hand.
2) CNN for training the model.


### Python  Implementation

1) Network Used- Convolutional Neural Network

If you face any problem, kindly raise an issue

### Procedure

1) First, you have to create a gesture database. For that, run `CreateGest.py`. Enter the gesture name and you will get 2 frames displayed. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
2) Repeat this for all the features you want.
3) Run `CreateCSV.py` for converting the images to a CSV file
4) If you want to train the model, run 'RPS_Model.py'
5) Finally, run `RPS_App.py` for playing Rock-Paper-Scissors via webcam.


### Contributors

##### 1) [Animesh Trivedi](https://github.com/pratima97ani/)
##### 2) [Chandra Shekhar pandey](https://github.com/indianspeedster)
##### 3) [Mahesh kumar singh](https://github.com/maheshkrsg)

 
 






