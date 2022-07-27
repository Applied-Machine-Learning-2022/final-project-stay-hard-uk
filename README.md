[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8127862&assignment_repo_type=AssignmentRepo)

# Sponsored by:
## [National Action Council for Minorities in Engineering(NACME)](https://www.nacme.org) Google Applied Machine Learning Intensive (AMLI) at the `PARTICIPATING_UNIVERSITY`

Developed by: 
- [Guysnove Lutumba](https://github.com/guysnove) - `Northern Kentucky University`
- [Ella Kapanga](https://github.com/Elle-Her) - `Univesity of Kentucky` 
- [Ricardo Medina](https://github.com/ricardoenocmedina) - `University of Texas` 
- [Allan Joseph](https://github.com/authenticArchitect) - `Stevens Institute of Technology`

#Stay Hard Team

## Description
 The objective of this project is to predict the level of distress for patients using sensor data. Students will find a solution to this problem using graph neural networks (GNNs) where sensors are represented as graph nodes and their proximity is represented by edges.
 
# Process Overview:
## 1. Building on top of ASSUAGE
 This project was built with the purpose of improving the Assuage app. Assuage was designed for remote symptom monitoring in rural cancer patients by asking survey based question in determining their whether or not they are distress. This project builds on top of the Assuage project. With our application health officals would use their patients biometrics collected through their Apple watches or Fitbits to determine health, instead of asking them questions.

## 2. Our Dataset
 The dataset used in this project was from the study, *Wearable and Automotive Systems for Affect Recognition from Physiology.* In this study researchers collect biometrics from nine individals across twenty-seven driving runs. Though only ten of the overrall driving runs were usable. The biometrics collect from this study were respiration rate (RESP), heart rate (HR), galvanic skin response (GSR),  electromyogram (EMG), blood volume pulse (BVP) and electrocardiograph (EKG). But for this project we only used RESP, HR, GSR and EMG.

## 3. Our Part
  This project we only used RESP, HR, GSR and EMG in measuring whether or not a patient is distress. Our parameter selection was influenced by the study, *Classification of Stress Recognition using Artificial Neural Network.* The study was primary focused on determined whether or not someone was stress or not. Stress is different from distress but there are similarities between the two. This study was able to determine when someone is stress with a 99% accuracy. As such, the same parameters where used in creating models to determine if someone is stress. We were able to get promising results but were not able to recreate the same results from the study. The model with the highest accuacy was a logregression model, with a 86% accuracy. 
  
  
  
## Usage instructions

1. Fork this repo
2. Change directories into your project
3. On the command line, type `pip3 install pyECG`
4. On the command line, type `pip3 install wfdb`
5. On the command line, type `pip install seaborn`
6. On the command line, type `pip install jupyter`
7. On the command line, type `pip install numpy`
8. On the command line, type `jupyter notebook`
9. Locate and open the file you download from this repo
