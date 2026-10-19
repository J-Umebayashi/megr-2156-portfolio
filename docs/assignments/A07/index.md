# A7 – Bracket FEA 

## Introduction
The assignment for this week is running FEA (finite element analysis) on the bracket I have been designing the past two assignments. We must run a minimum of three simulations, and record what design changes are made to the bracket between each simulation. 

## Design 1

<img width="360" height="531" alt="Design 1 ss" src="https://github.com/user-attachments/assets/e00268f7-3a3d-46ac-87a3-dab9ba61b39f" />

## Design 1 Data


| FEA # | Element # | Safety Factor | Max Stress | Max Deflection |
| --- | --- | --- | --- | --- |
| 1 | 13547 | 0.1 | 2.735e9 | 8.603e0 |
| 2 | 27844 | 0.099 | 2.785e9 | 8.712e0 |
| 3 | 62303 | 0.092 | 2.973e9 | 8.970e0 | 

These three photos are from the first FE analysis.

<img width="732" height="475" alt="fea 1 11" src="https://github.com/user-attachments/assets/057b816e-8280-4b0a-a056-8ac97ed96730" />

<img width="799" height="491" alt="fea 1 12" src="https://github.com/user-attachments/assets/f007fd09-0464-4161-a108-e9eeae386a26" />

<img width="745" height="445" alt="fea 1 14" src="https://github.com/user-attachments/assets/730e792b-dd25-4e1b-9a5c-4be3dc35e704" />

<img width="700" height="481" alt="FEA 1 21" src="https://github.com/user-attachments/assets/3f5d0076-884a-40cb-8b69-1129ca338972" />

<img width="672" height="467" alt="fea 1 22" src="https://github.com/user-attachments/assets/0f3893d4-fd1f-4936-951d-e31048c137fd" />

<img width="803" height="523" alt="fea 1 23" src="https://github.com/user-attachments/assets/1687189d-2d3f-40a2-89cc-d5445646f8b3" />

<img width="644" height="381" alt="fea 1 31" src="https://github.com/user-attachments/assets/49b9f680-799b-4114-8c4c-ea222591383f" />

<img width="666" height="382" alt="fea 1 32" src="https://github.com/user-attachments/assets/d8c7c9ac-cb8f-4ef9-988a-692e2cdd8f61" />

<img width="651" height="393" alt="fea 1 33" src="https://github.com/user-attachments/assets/36b625fb-909e-4da2-adb3-3b24de928545" />

## Design 1 Optimization

The glaring feature issue from this first round of FEA is the piece mounting the hanger to the bracket. It has a very low safety factor and is failing in every simulation. I am going to thicken this piece before re-running FEA for Design 2.

## Design 2

<img width="357" height="491" alt="Design 2 ss" src="https://github.com/user-attachments/assets/a8f10401-8406-4456-a881-dfce0c02c188" />

For this design I thickened the support on the bottom of the bracket. 

## Design 2 Data

| FEA # | Element # | Safety Factor | Max Stress | Max Deflection |
| --- | --- | --- | --- | --- |
| 1 | 12477 | 0.73 | 3.785e8 | 6.090e-1 |
| 2 | 25397 | 0.68 | 4.068e8 | 6.165e-1 |
| 3 | 62720 | 0.58 | 4.737e8 | 6.233e-1 | 

Below are photos from each FE simulation, in order from 1 to 3.

<img width="701" height="451" alt="Fea 2 11" src="https://github.com/user-attachments/assets/c5b1fdb7-cbac-46d2-adf9-3f9e3ecee235" />

<img width="736" height="473" alt="Fea 2 12" src="https://github.com/user-attachments/assets/72e46b22-8ed4-4dfc-a074-239ae03944d2" />

<img width="770" height="501" alt="Fea 2 13" src="https://github.com/user-attachments/assets/f1129ca5-d8b4-4aaf-8b76-a9f8e91ab045" />

<img width="756" height="510" alt="fea 2 21" src="https://github.com/user-attachments/assets/646730b1-5f8b-4c7a-afc2-51b0119070cc" />

<img width="751" height="518" alt="fea 2 22" src="https://github.com/user-attachments/assets/135e0c67-cffe-492a-8132-1086644c5413" />

<img width="744" height="504" alt="fea 2 23" src="https://github.com/user-attachments/assets/675e33d8-5dba-434b-8b44-518da038aecb" />

<img width="756" height="555" alt="fea 2 31" src="https://github.com/user-attachments/assets/1b80e43d-ac74-4a11-b2c6-af47d0eec5aa" />

<img width="709" height="507" alt="fea 2 32" src="https://github.com/user-attachments/assets/b5664ea0-b923-4dcc-b62c-048aa6245a1e" />

<img width="725" height="509" alt="fea 2 33" src="https://github.com/user-attachments/assets/b53846f9-6da3-4e4d-88b5-8959050ef666" />

## Design 2 Optimization
Design Two is experiencing the same issues as Design One. The safety factor has slightly improved, but not being a meaningful amount in the overall design. I think I am going to need to take a massive swing at the third design to achieve the safety factor goal of 4, considering how far off the current design is.

## Design 3 

<img width="392" height="607" alt="Design 3 ss" src="https://github.com/user-attachments/assets/70d2c872-91d3-4e7c-bfc3-4436a126495f" />

Here is my update for design 3. I took a big swing at the support by adding a second mount from the body of the bracket to the hanger. I had to extend the cylinder length to ensure that the strap would still fit the bracket. I made this change because I needed a big increase in safety factor. 

## Design 3 Data

| FEA # | Element # | Safety Factor | Max Stress | Max Deflection |
| --- | --- | --- | --- | --- |
| 1 | 14307 | 1.5 | 1.779e8 | 6.000e-1 |
| 2 | 25321 | 1.4 | 2.029e8 | 6.031e-1 |
| 3 | 63718 | 1.1 | 2.575e8 | 6.073e-1 | 

Below are screenshots from the FEAs run on this design model. Every round of FEA had an increased mesh made for more precise results. 



