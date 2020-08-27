# Image_Processing
Detection of face and eyes.

This is the basic project of Image processing which involves given an image which can consist of some faces and non faces, this will identify all the faces among all
things present in an image.Though this project is simple yet very insightful and clears most of your concepts regarding opencv. 
Basic conceptual knowledge of opencv is required before proceeding implementation of face detection algorithm.

What exactly we are trying to do is to train the computer to understand what a face is and what a non face is.Once a computer is trained ,it will extract certain features
and everything will be stored in a file.All we do is we take that file,if we get any new input image,check the  features from the file and apply it to the image.So if it is
passes through all the stages of feature comparison,you say that it a  face else it is not a face.

So we have already a trained data with all the features that have been trained and now we do is in any system,we just have the train data and using that data we
just classify the given name image as a face or non face just by refering to the data that we already have.

How the haar cascade object detection works?
Object detection using haar feature based cascade classifier is an effective object detection method. It is a machine learning based approach whre a cascade function
is trained from a lot of postitive and nagative images. It is then used to detect objects in other images.

Cascading: It is a particular case of ensemble learning based on the concatenation of several classifiers using all info collected from the
output from a given classifier as additinal info for the next classifier in the cascade.

Initially the algo needs a lot of postive images(with faces)negative images(without faces) to train the classifier.Then we need to extract features from it.

Haar Features: Haar features are similar to the convolution kernels which are used to detect the presence of that feature in the given image.
