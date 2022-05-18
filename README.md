# SleepDetection

This repository contains information regarding the M2Sleep data set and the data analysis steps performed in paper [1].

If you use the scripts for the identification of sleep-wake phase and sleep quality as well as the data set presented in this paper, please cite paper [1] as follows: 

[1] S. Gashi, L. Alecci, E. D. Lascio, M. E. Debus, F. Gasparini and S. Santini, "The Role of Model Personalization for Sleep Stage and Sleep Quality Recognition Using Wearables," in IEEE Pervasive Computing, doi: 10.1109/MPRV.2022.3164334.

The paper is available at https://ieeexplore.ieee.org/document/9768202. 

Please do not hesitate to contact us at silvia.santini@usi.ch if you have any questions regarding the paper and the data set.


## M2Sleep data set

M2Sleep (*Monitoring of Sleep using Personal Devices*) is a data set collected by the research group of Prof. Silvia Santini at the Faculty of Informatics of Università della Svizzera italiana (USI), in Lugano, Switzerland. The data set was collected from 16 participants over 30 days in ambulatory settings. 

### Collected data
- *Physiological data*: electrodermal activity, skin temperature, 3-axis acceleration and blood volume pulse. Physiological data was collected using the Empatica E4 (https://www.empatica.com/research/e4/) worn on the non-dominant hand. 

- *Behavioral data*: time of phone lock/unlock events, screen on/off, application from which a notification arrived and whether the notification was clicked or not, proximity of the phone screen to any surface, and ambient light intensity. Behavioral data was collected using a custom made Android application implemented by our group.

- *Self-reported data*: 632 self-reports regarding the sleep and wake up time and 312 self-reports regarding sleep quality. The self-reported data was collected using three tools, an Android application, a laptop widget and a pen-and-paper diary.

- *Questionnaires*: the Pittsburg Sleep quality Index (PSQI), the Big Five Inventory (BFI), Munich ChronoType Questionnaire (MCTQ) and demographics questionnaire. 

All participants signed an informed consent agreement and agreed with their data being used and shared for research purposes. The study was reviewed and approved by our Faculty's representative for research ethics. Participants were compensated with an initial amount of 20 CHF for enrollment and 1 CHF for each day upon collection of physiological data and self-reports regarding sleep and wake up times as well as sleep quality for 30 days. 

The data collection set up and summary of the data analysis performed in paper [1] is presented in the figure below. 

![alt text](https://github.com/shkurtagashi/SleepDetection/blob/master/Our_approach.png)

Please contact us at silvia.santini@usi.ch to make a request regarding the data set. 

## Data analysis

The repository contain snippets of code for replicating the data analysis steps as in paper [1]. 

- *FeatureExtraction*: Explains how to extract the time-, frequency- and time-frequency-domain features. 
- *Classification_Pipeline*: Reports how to run the personalized and population models described in the paper.

For preprocessing the data please refer to this notebook: https://github.com/shkurtagashi/EDArtifact/blob/master/EDArtifacts_Detection/EDArtifacts_Detection.ipynb