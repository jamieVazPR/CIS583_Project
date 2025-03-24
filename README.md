# Disaster Tracking: Infrastructure Damage Recognition from Image Data

Natural disasters are a various global phenomenas that occur, either man-made or naturally, which are capable of causing severe damage to infrastructure, impact/endanger our daily lives, and even cause shift in how necesseties are distributed. Various factors going into producing, predicting, or even analyzing these phenomenas; however the project's goal is to study how computer vision can aid in analyzing areas of disaster to provide estimate on damages to infrastructure.

Computer Vision is a branch from Artificial Intelligence that focuses on pre-processing, processing, and analyzing data contents in image/video format in static/dynamic methods (Static = still images, Dynamic = Real-Time videos). As per IBM, https://www.ibm.com/think/topics/computer-vision, Computer Vision manages large number of data to efficiently provide context to the information is being fed. In the case of this project, the context are verifying whether an image can classify under Disaster or Non-Disaster. As these phenomenas keep increasing in destructive power and affecting ata  wider scale, as per NOAA's study shown in https://www.climate.gov/news-features/blogs/beyond-data/2023-historic-year-us-billion-dollar-weather-and-climate-disasters, we must continue studying aftermath assessments to recover quicker due to this constant global change. The following mission statements, goals, and resources are shown below:



### Project Statement

Show case the utilization of Computer Vision techniques, in this case Convolutional Neural Networks (CNN), to perform classification on a series of images related to natural disasters. These images will under two categories : 1) Disaster, and 2) Non-Disaster to illustrate how Computer Vision can assist in identifying infrastructure damage for first-responders to assert cost, resources, and time to provide in various sectors.

### Project Limits

Due to the model being composed of a standard CNN, the project is limited on the following:

1) Image quality - Some images due to formatting can result in low quality outputs that can affect model performance.
2) Hardware - Local Machines are utilized to run the model to assess performance. No HPC has been provided or domain to execute project.
3) Data Size - Since CNN's require extensive amount of data, we are restricted to utilizing Kaggle's Dataset which guarantees an acceptable size of data.
4) Data Set - Since this field is monitor mostly by satellite data and majority falls outside of Unclassified Category, we utilized publicly available dataset from Kaggle which includes images from inside earth's atmosphere, i.e. from planes, from drones, from helicopters, and even on ground. 

### Project Goals

The project focuses on utilizing a pre-trained model to assess classification analysis for the following goals:

1) Identify images under disaster category at a threshold above 50%.
2) Identify images under non-disaster category at a threshold above 50%.
3) Saved Model that can be utilized by the public.
4) Report documenting the results and model architecture.

For further information on the project, please refer to the official Confluence Page issued under :
- https://cis553-2024.atlassian.net/wiki/spaces/SD/pages/8519681/Disaster+Tracking+Debris+Recognition+from+Image+Data

## Example of Model Output and Model Architecture

![Model Architecture](https://github.com/jamieVazPR/CIS583_Project/blob/main/Images/ModelArchitecture.png)

![Model Output](https://github.com/jamieVazPR/CIS583_Project/blob/main/Images/ModelOutput.png)

![Model Plot](https://github.com/jamieVazPR/CIS583_Project/blob/main/Images/ModelPlot.png)