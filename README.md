Skin-strain-estimation-using-high-precision-camera
==================================================
<p>
This project investigates the relationship between different grasp postures of the hand and the skin strain changes that happen on the dorsal surface of the hand for each poses. I wear 12 reflective markers on the dorsal surface of the hand and capture the grasp videos from a high precision camera system. The changes in the positions of this marker set is recorded in a csv file with time as a reference. 
=========================================
The matlab program takes in a CSV file which is formed by accounting the position changes (3D cordinates) of each marker. Each video thus produces a 36 dimension data which is converted into a 3 dimensional data using a dimensionality reduction technique called Principal Component Analysis (PCA). Then I train a Support Vector Machine (SVM) to classify these gestures. 
</p>
