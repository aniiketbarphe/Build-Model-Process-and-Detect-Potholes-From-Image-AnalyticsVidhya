![Final-Image](https://user-images.githubusercontent.com/84449238/206859778-88bea8b7-367d-4605-81ce-97bb60d63b49.jpg)

# Build-Model-Process-and-Detect-Potholes-From-Image-AnalyticsVidhya

Build an AI model to save lives


Build a computer vision-based technology to process and detect the potholes present in an image.



Problem Statement


Over the past few years, Sihao has seen exponential growth in the number of vehicles on the road. As a  result, the increase in the number of vehicles on road gave rise to the number of road accidents. According to a study, one fatal road accident occurs every 5 minutes in the country, and 8 die on roads every hour. This has become a major concern in the country. One of the primary causes of these road accidents is the management and maintenance of the roads.


Potholes on roads can cause serious accidents, and any vehicle traveling at some decent speed can lose its track due to them. In the case of four-wheeler vehicles, potholes can cause severe damage to wheels and tires. More specifically, when it comes to two-wheelers like motorbikes, these vehicles are more prone to accidents due to potholes as the tendency to cause imbalance is very high and can lead to fatalities.


Concerned by the increasing number of accidents caused by potholes, the government of Sihao has started initiatives and campaigns to install cameras in the most accident-prone cities and capture the feed to detect the potholes. In this hackathon, as a Computer Vision Learner or Expert, you will apply image processing techniques to process the images and detect the potholes. This will assist the government to identify the extreme potholes depending on their size and handle them as the earliest.



About the Dataset


You are provided with the sample dataset containing 1230 images captured through different devices. Out of which, 674 images contain annotations i.e. class and bounding boxes. An image can contain single/multiple potholes or no potholes. The dataset includes images with different scales, backgrounds, and weather conditions. As a part of model building, you need to tackle these challenges.



Data Dictionary


You are provided with 3 files- train.zip, test.zip, and sample_submission.zip



Train set


train.zip contains 2 files: images and labels.csv.

The images folder includes the images for model training.
labels.csv includes the annotations for the training set. The format of labels.csv is given below-

![IMG1](https://user-images.githubusercontent.com/84449238/206859341-57eb2805-67e8-4efa-a71d-2f754041a800.JPG)

Test set


test.zip contains only the images folder. You need to predict the potholes and bounding boxes present in the test set.




Submission File Format 


sample_submission.zip contains sample_submission.csv and a starter notebook that gets you started with building the benchmark model for detecting the potholes from the image. sample_submission.csv contains 7 variables: ImageID, LabelName, XMin, XMax, YMin, YMax, Conf. Your solution file must follow a format similar to that of the sample submission file.


Note that

Your solution file will contain the predictions for the images that contain only bounding boxes present in the test set.
If there is no bounding box detected for an image in the test set, do not include these images in the solution file.

![IMG2](https://user-images.githubusercontent.com/84449238/206859356-a38c85ec-b76e-4a5a-8511-05cffc71c11e.JPG)


Evaluation metric


The evaluation metric for this hackathon would be mAP@0.5:0.95. 



Public and Private Split


Test data is further divided into Public (40%) and Private (60%) data.


Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.

Competition Link:- https://datahack.analyticsvidhya.com/contest/dataverse-hack/#LeaderBoard 
