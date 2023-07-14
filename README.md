# Hannibal-ADS(Hannibal Air Defense System)
We developed a sky monitoring system, called HANNIBAL ADS that is designed to alert users when a “Nefarious” mini-UAV has entered into the monitored airspace. It can detect, track and locate the target, monitor in real time, receive the target information of various imaging sensors such as RGB sensor, thermal sensor, and laser sensor in real time. 
So, HANNIBAL ADS system employs powerful AI video analytic algorithms to accurately distinguish between mini-UAVs and other flying objects such as birds, and airplane. 
To sum up, our contributions in this proposed monitoring system are listed as follows.
  We collect images of mini-UAVs in a real environment, most of which contain flying mini-UAVs at various locations. To avoid redundant images in our detection dataset, just 10% of the total video data recorded by a Dahua multi- sensor Network PTZ camera "DH-TPC-PT8621C" [13] was extracted and collected. Subsequently, we build a custom dataset, called “mini-UAV detection dataset”, which provides a benchmark to evaluate the performance of the proposed detection model.  
 We develop a mini-UAV detection model by redesigning the YOLOv5 architecture. Moreover, we implement key modifications to the network to improve the behavior of the model in terms of performance. So, in the redesigned model which called “modified-YOLO”, we have inserted a fourth level of feature maps collector to focus on small flying object detection in air picture. 
We build a mini-UAV tracking dataset of RGB video sequences using Dahua multi-sensor camera "DH-TPC-PT8621C". So, 25 fully annotated video sequences with 05 attributes are used in our tracking dataset to facilitate tracking evaluation.
We propose to improve the muni-UAVs re-identification (Re-ID) by using a multi-Level feature fusion-based CNN as a feature extractor in the appearance feature stage of Deep-
SORT. Thus, the appearance feature is a more discriminative representation of the object, which can distinguish between objects effectively when they are similar. Therefore, our goal
is to improve the tracking accuracy and robustness in complex scene, effectively reducing the number of ID switches and tracklet segments.
To support AI-powered optical detection and tracking algorithms, we have developed a Software called Data Analysis and Management Software DAMS) that used to the HANNIBAL ADS. 

## Table of Contents
- Installation
- Usage
- Features

## Installation
The hardware installation is shown in figure installation.jpg, while the software installation is presented in the readme file of the DAMS project.

## Usage
After installing the software and hardware, launch the software and click on the administration field to define the configuration. The system is now ready for drone detection and tracking. 

## Features
- Detection, identification and tracking of drones 
The system must be able to detect and identify the drones in the field of view of the camera as well as predicting the position and tracking it   
- Neutralization of drones 
The system shall be able to jam the drones detected by the positioner control 
- Visualization of video streams and simulation of events on a map
The system shall be able to estimate the distance and position of the detected UAVs and project these data on a map  
- Hardware configuration
The system must provide graphical interfaces that allow the management of hardware equipment such as camera, positioner, gain etc...   
- Privilege management 
The system must be able to distinguish and classify users and provide services according to these types as administrator, user, observer.  
