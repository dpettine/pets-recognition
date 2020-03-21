# dogs-recognition
This project provides an HAAR weak classifier trained to detect dog faces.
The HAAR classifier is built upon 1000+ real positive samples and 3000 negatives.
The training parameters used are:
numStages: 20 
minHitRate 0.99 
maxFalseAlarmRate 0.5 
w-h:  40-40 

the training process was solely based on official Open CV documentation.
Please refer to https://docs.opencv.org/trunk/dc/d88/tutorial_traincascade.html for the full documentation

The project also includes a simple python example of usage.
To test it just download the full package on your computer. 
Run the dogs.py script. The sample pictures in the 'pets' directory will be processed. Pictures containing a dog face will be copied in the 'rec' subfolder with the ROI (Region Of Interest) evidenced with a rectangle.
Some negative samples are included in the 'pets' dir to test the classifier robustness.

