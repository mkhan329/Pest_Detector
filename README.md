# Pest_Detector
CS 445 Final Project

Project Proposal: https://docs.google.com/document/d/1yF2iwG_wJvRx8-SsTcDrQyoJbetWRxVR/edit?usp=sharing&ouid=109848048592042249462&rtpof=true&sd=true
Project Report: https://docs.google.com/document/d/1wVQ3E7Hiw7sqbSgm84wm5opMp23XY6TG/edit?usp=sharing&ouid=109848048592042249462&rtpof=true&sd=true

Get the dataset from kaggle: https://www.kaggle.com/datasets/rtlmhjbn/ip02-dataset

Running OCR Code:
Download the OCR zipfile
2 images from the dataset are provided: “train/92/65505.jpg” and “train/92/65536.jpg”
Put the image path in the “img_path” variable
Run the cells
Note: The code might not run in a regular jupyter notebook but will run in google colab


Running Template Matcher:
Download the ‘TestData’ folder containing 100 test images and a template image (Aphids)
Download the ‘MatchedImages’ folder. It is the destination folder for the results.
In the jupyter notebook ‘EdgeDetection.ipynb’, run the cells.
You may access results in the ‘MatchedImages’ folder. You may also try other test images from the IP102 database.


Running Neural Network:
Download the “pest_tf” zip file and “test_pest_tf.ipnyb” notebook
In “pest_tensorflow.ipnyb”:
Specify the path of the image repository and run the create_train_data method
Run the cell to initialize the Convolutional Neural Network, specify path of "training_1/cp.ckpt"
You do not need to train the neural network, simply run the cell which loads the weights into the CNN
In “test_pest_tf.ipnyb”
You can test the neural network on different images to see its prediction, simply change the num value to select different images
