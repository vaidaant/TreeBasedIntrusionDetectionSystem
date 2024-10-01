# TreeBasedIntusionDetectionSystem
# Overview:
Tree-based IDS use of autonomous vehicles (AVs) is a promising technology in Intelligent Transportation Systems (ITSs) to improve safety and driving efficiency. Vehicle-to-everything (V2X) technology enables communication among vehicles and other infrastructures. However, AVs and the Internet of Vehicles (IoV) are vulnerable to different types of cyber-attacks such as denial of service, spoofing, and sniffing attacks. An intelligent IDS is proposed in this paper for network attack detection that can be applied not only to the Controller Area Network (CAN) bus of AVs but also to general IoVs. The proposed IDS utilizes tree-based ML algorithms including decision tree (DT), random forest (RF), extra trees (ET), and Extreme Gradient Boosting (XGBoost). The results from the implementation of the proposed intrusion detection system on standard data sets indicate that the system has the ability to identify various cyber-attacks in the AV networks. Furthermore, the proposed ensemble learning and feature selection approaches enable the proposed system to achieve a high detection rate and low computational cost simultaneously.

# Dataset:

1)CICIDS_2017_sample(1).csv (already uploaded)

2)2 input files are present in the form of CSV (this is required while running appa.py)

# User Interface designing output :

Input webpage(Taking the top 15 features from the user and selecting models out of 4 and 1 and predict buttons which help to tell types of IDS identifies wrt that model 7 IDS we are going to predict using class labels as:

0  BENIGN

1  Bot

2  BruteForce

3  DoS

4  Infiltration

5  PortScan

6  WebAttack

![WhatsApp Image 2024-10-02 at 02 00 22_d2ecb876](https://github.com/user-attachments/assets/3b55a22f-d029-4e66-a5c6-92c2696c78e9)
![WhatsApp Image 2024-10-02 at 02 00 23_01db0781](https://github.com/user-attachments/assets/127d108b-bafd-4d40-9e17-c320cd1f8b4d)




Same procedure but now the input is taken from the CSV file(input1,input2)
![WhatsApp Image 2024-10-02 at 02 00 22_0bc93476](https://github.com/user-attachments/assets/9b50cda2-24db-4097-80e8-fd76f0be3daf)

Output webpages:

![WhatsApp Image 2024-10-02 at 02 00 22_0d1806b7](https://github.com/user-attachments/assets/4791615c-3d63-453f-9f69-a6336ffed869)

Software Tools: VSCode,pycharm, python latest version should be installed

Requirements: present in requirements.txt

Open the folder in any of the software tools(mentioned above) and then run app.py and appa.py you will get results.


