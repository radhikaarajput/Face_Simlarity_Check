# Face_Simlarity_Check



To develop a method for face verification which when given two input images, one masked and one unmasked, is able to detect if the two images belong to the same person or not.
Our problem of verifying faces can be thought of as a classification problem.
Given a face image space E, we are trying to determine a function: 
f: E x E-> {0, 1} that associates the pair (x1, x2) to 0 if it is a genuine pair, and to 1 if it is an imposter pair
