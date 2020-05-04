# ASL_SIGN_PREDICTOR
The first thing for any project is it's need...So let's start with that...Let's imagine that there are two person among which one is deaf and the other is mute...so how do they communicate with other people?? One cannot speak and the other cannot listen...so our aim is to provide a way of communication for them,it is not limited to this,but it also helps in having the conversation with the one who doesn't understand sign language...So for this we have used Kaggle asl dataset, performed Skin Masking and then built a model using CNN to give voice to the sign language.This project converts the signs into text which then also gets converted into voice.
This is a team project of three members namely Sourav Jain,Simardeep Singh and Parag Mittal.The link for the dataset used for this is "https://www.kaggle.com/grassknoted/asl-alphabet"
# Context
The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes.
# Content
The training data set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for SPACE, DELETE and NOTHING. These 3 classes are very helpful in real time applications, and classification. The test data set contains a mere 29 images, to encourage the use of real world test images.
Image:https://www.nidcd.nih.gov/sites/default/files/Content%20Images/NIDCD-ASL-hands-2014.jpg
Libraries used for this project are pandas,os,numpy,sklearn,skimage,keras,cv2,etc.
