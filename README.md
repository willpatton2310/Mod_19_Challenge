# Mod_19_Challenge

## Our Task
Our task was to help our client create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Methodology
Utilizing a Retified Linear Unit function, we created a neural network utilizing the TensorFlow function in Python.  

## Results
In our original run, we created a neural network with 80 neurons and 50 hidden layers.  Our model accuracy was 72.59%.  We were tasked with trying to reach 75% accuracy so, in our second attempt, we removed the "Organization" feature from the data as it seemed to be noise.  Our model was then 72.4% accurate.  So in a second attempt, we added increased the neurons (to 100).  Our model then was 72.31% accurate.  In our third attempt, we added hidden layers (to 50) and our model was 72.28% accurate.

### Conclusion
Our coding was sound and our model worked, but we clearly need more practice with accuracy.  Perhaps in the future we can apply a sigoud model as our outputs are all within a range between 0 and 1.
