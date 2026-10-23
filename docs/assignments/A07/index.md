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

<img width="680" height="551" alt="fea 1 11" src="https://github.com/user-attachments/assets/e09a13c7-0ccd-405f-9b38-203053f78967" />

<img width="630" height="551" alt="fea 1 12" src="https://github.com/user-attachments/assets/9aeae20d-015f-43bf-8da8-938fc1c7f2c5" />

<img width="594" height="533" alt="fea 1 13" src="https://github.com/user-attachments/assets/a7977412-05a2-4d94-a88f-9cfb7263d62c" />

<img width="747" height="532" alt="fea 1 21" src="https://github.com/user-attachments/assets/2731d0c2-7ac4-442f-b4c8-03fc425edd5b" />

<img width="743" height="530" alt="fea 1 22" src="https://github.com/user-attachments/assets/cb68fbe7-57e2-4eba-9186-80e315d1e27d" />

<img width="683" height="512" alt="fea 1 23" src="https://github.com/user-attachments/assets/fe5ff2be-0594-4da9-81e5-45ae40f40a13" />

<img width="644" height="381" alt="fea 1 31" src="https://github.com/user-attachments/assets/8826ce66-7470-4d4b-b3cf-5689bf3c2ebe" />

<img width="666" height="382" alt="fea 1 32" src="https://github.com/user-attachments/assets/c730007f-f65d-4d83-a9a4-1b9c979a1a2a" />

<img width="596" height="368" alt="fea 1 34" src="https://github.com/user-attachments/assets/f19ebce7-17c8-465a-bc8f-2bc3a58a814e" />

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

<img width="682" height="489" alt="FEA 3 11" src="https://github.com/user-attachments/assets/bdd87d02-0a47-4903-a534-6f1e4b48daeb" />

<img width="652" height="483" alt="FEA 3 12" src="https://github.com/user-attachments/assets/4b78a7b6-ca7d-4cac-bbe4-de0a2e400f0d" />

<img width="648" height="466" alt="FEA 3 13" src="https://github.com/user-attachments/assets/4ff4b8a9-b0be-4795-899d-85eb8d51ae7b" />

<img width="656" height="483" alt="FEA 3 21" src="https://github.com/user-attachments/assets/7759206f-b131-4e7c-9140-57824abf0d2c" />

<img width="628" height="476" alt="FEA 3 22" src="https://github.com/user-attachments/assets/fa3564f7-5294-48ca-a582-c04cfa2c86c5" />

<img width="645" height="480" alt="FEA 3 23" src="https://github.com/user-attachments/assets/4bedc16d-f1aa-4b4c-9e5a-f68e319c33c9" />

<img width="643" height="489" alt="FEA 3 31" src="https://github.com/user-attachments/assets/b9eae39a-8cf7-4966-a9d1-74b9327bd0b7" />

<img width="660" height="475" alt="FEA 3 32" src="https://github.com/user-attachments/assets/db9da3ef-8ed6-4126-85d7-42b80bfff467" />

<img width="634" height="461" alt="FEA 3 33" src="https://github.com/user-attachments/assets/8252952a-b1c5-4ca0-905f-7b693d43d0c8" />

## Design 3 Reflection

The design changes made between 2 and 3 had the most impact on the FEA results. The biggest gain in safety factor was found with the addition of the second support on the bottom of the bracket. Seeing the results of this design change, I realized I should have made this change from Design 1 to Design 2 instead. I was surprised to see the minimum safety factor move completely from the bottom of the bracket to the top. 

## Reflections

The biggest lesson I learned from this assignment is the fact that I should have made bigger changes earlier in the design iterations. The changes from 2 to 3 made the biggest difference in the FEA, whereas the updates from 1 to 2 only made a slight difference. I should be more willing to try bigger changes to get the results needed. When running the analysis on the third design, I noticed the FEA process took longer to compute, which I assume is a side effect of having a more complicated part to analyze. This assignment has taken me about 7 hours to complete. 

## Appendix

[Bracket Model 2 Download](https://drive.google.com/file/d/1VKrv2iOdLvIl_9jzSrC_tfglzMj8p4Xx/view?usp=sharing)

[Bracket Model 3 Download](https://drive.google.com/file/d/1BS54wyY13fwin73DTgGTTHO56KCzJy_s/view?usp=sharing)

FEA Mesh slider values

<img width="151" height="293" alt="Mesh Qual  1" src="https://github.com/user-attachments/assets/91fdf53f-0109-4ffc-ba44-e9af046f4d4d" />

<img width="143" height="306" alt="Mesh Qual  2" src="https://github.com/user-attachments/assets/60384e75-bb3b-4f58-a7c5-43d08522aed7" />

<img width="147" height="305" alt="Mesh Qual  3" src="https://github.com/user-attachments/assets/63716c69-9276-4802-8392-73013e079673" />


