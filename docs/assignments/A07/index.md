# A7 – Bracket FEA 

## Introduction
The assignment for this week is running FEA (finite element analysis) on the bracket I have been designing the past two assignments. We must run a minimum of three simulations, and record what design changes are made to the bracket between each simulation. 

## Design 1

<img width="360" height="531" alt="Design 1 ss" src="https://github.com/user-attachments/assets/e00268f7-3a3d-46ac-87a3-dab9ba61b39f" />

## Design 1 Data


| FEA # | Element # | Safety Factor | Max Stress | Max Deflection | Mass |
| --- | --- | --- | --- | --- | --- |
| 1 | 1318 | 0.17 | 2.844e9 | 5.515e0 | 0.43 |
| 2 | 8514 | 0.11 | 2.614e9 | 8.430e0 | 0.43 |
| 3 | 62303 | 0.092 | 2.973e9 | 8.970e0 | 0.43 |

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

| FEA # | Element # | Safety Factor | Max Stress | Max Deflection | Mass |
| --- | --- | --- | --- | --- | --- |
| 1 | 1217 | 0.97 | 2.846e8 | 5.515e-1 | 0.45 |
| 2 | 8652 | 0.76 | 3.636e8 | 6.059e-1 | 0.45 |
| 3 | 62720 | 0.58 | 4.737e8 | 6.233e-1 | 0.45 |

Below are photos from each FE simulation, in order from 1 to 3.

<img width="633" height="530" alt="fea 2 11" src="https://github.com/user-attachments/assets/6cf5709b-177e-433b-98d2-d2e9299062cf" />

<img width="644" height="544" alt="fea 2 12" src="https://github.com/user-attachments/assets/5f5d1ea7-7058-425d-97b2-fbb45e8a45a2" />

<img width="618" height="517" alt="fea 2 13" src="https://github.com/user-attachments/assets/9fca1ef0-2ab3-4ac4-bdde-946ba62fc89c" />

<img width="653" height="543" alt="fea 2 21" src="https://github.com/user-attachments/assets/1e52dd95-72c4-4800-8420-4922de8731b4" />

<img width="654" height="542" alt="fea 2 22" src="https://github.com/user-attachments/assets/c333312f-e97c-4ef3-a829-e0db7cc5dc9a" />

<img width="669" height="516" alt="fea 2 23" src="https://github.com/user-attachments/assets/4b25f6a5-cfe2-4c3f-9152-1a742f7f562e" />

<img width="756" height="555" alt="fea 2 31" src="https://github.com/user-attachments/assets/1b80e43d-ac74-4a11-b2c6-af47d0eec5aa" />

<img width="709" height="507" alt="fea 2 32" src="https://github.com/user-attachments/assets/b5664ea0-b923-4dcc-b62c-048aa6245a1e" />

<img width="725" height="509" alt="fea 2 33" src="https://github.com/user-attachments/assets/b53846f9-6da3-4e4d-88b5-8959050ef666" />

## Design 2 Optimization
Design Two is experiencing the same issues as Design One. The safety factor has slightly improved, but not being a meaningful amount in the overall design. I think I am going to need to take a massive swing at the third design to achieve the safety factor goal of 4, considering how far off the current design is.

## Design 3 

<img width="392" height="607" alt="Design 3 ss" src="https://github.com/user-attachments/assets/70d2c872-91d3-4e7c-bfc3-4436a126495f" />

Here is my update for design 3. I took a big swing at the support by adding a second mount from the body of the bracket to the hanger. I had to extend the cylinder length to ensure that the strap would still fit the bracket. I made this change because I needed a big increase in safety factor. 

## Design 3 Data

| FEA # | Element # | Safety Factor | Max Stress | Max Deflection | Mass |
| --- | --- | --- | --- | --- | --- |
| 1 | 1306 | 1.9 | 1.425e8 | 5.849e-1 | 0.55 |
| 2 | 8680 | 1.6 | 1.703e8 | 5.978e-1 | 0.55 |
| 3 | 63718 | 1.1 | 2.575e8 | 6.073e-1 | 0.55| 

Below are screenshots from the FEAs run on this design model. Every round of FEA had an increased mesh made for more precise results. 

<img width="627" height="509" alt="fea 3 11" src="https://github.com/user-attachments/assets/d922c83d-4a04-4a47-91fa-25e9a85b0acc" />

<img width="599" height="499" alt="fea 3 12" src="https://github.com/user-attachments/assets/5842532c-f66c-4f96-92da-a1523586a76f" />

<img width="612" height="484" alt="fea 3 13" src="https://github.com/user-attachments/assets/40605dcd-91eb-4860-b8c6-1515e8608ee9" />

<img width="660" height="503" alt="fea 3 21" src="https://github.com/user-attachments/assets/b04011df-e8aa-4dd1-bf59-952450b08897" />

<img width="633" height="523" alt="fea 3 22" src="https://github.com/user-attachments/assets/adf5684e-5727-4562-96a9-0d80ae94e814" />

<img width="616" height="482" alt="fea 3 23" src="https://github.com/user-attachments/assets/ae354cc2-f735-46bb-be88-aa2eb078f645" />

<img width="643" height="489" alt="FEA 3 31" src="https://github.com/user-attachments/assets/b9eae39a-8cf7-4966-a9d1-74b9327bd0b7" />

<img width="660" height="475" alt="FEA 3 32" src="https://github.com/user-attachments/assets/db9da3ef-8ed6-4126-85d7-42b80bfff467" />

<img width="634" height="461" alt="FEA 3 33" src="https://github.com/user-attachments/assets/8252952a-b1c5-4ca0-905f-7b693d43d0c8" />

## Design 3 Reflection

The design changes made between 2 and 3 had the most impact on the FEA results. The biggest gain in safety factor was found with the addition of the second support on the bottom of the bracket. Seeing the results of this design change, I realized I should have made this change from Design 1 to Design 2 instead. I was surprised to see the minimum safety factor move completely from the bottom of the bracket to the top. 

## Reflections

The biggest lesson I learned from this assignment is the fact that I should have made bigger changes earlier in the design iterations. The changes from 2 to 3 made the biggest difference in the FEA, whereas the updates from 1 to 2 only made a slight difference. I should be more willing to try bigger changes to get the results needed. I noticed the vast difference between the course mesh FEAs and the fine mesh. The computation time is noticeably longer for the fine mesh. I am curious why I had to run all three FEAs for each design, as none of my FEAs converged to 7 percent. This assignment has taken me about 7 hours to complete. 

## Appendix

[Bracket Model 2 Download](https://drive.google.com/file/d/1VKrv2iOdLvIl_9jzSrC_tfglzMj8p4Xx/view?usp=sharing)

[Bracket Model 3 Download](https://drive.google.com/file/d/1BS54wyY13fwin73DTgGTTHO56KCzJy_s/view?usp=sharing)

FEA Mesh slider values

<img width="140" height="237" alt="Mesh Qual  1" src="https://github.com/user-attachments/assets/01652131-9b4a-41b9-be5c-430a3c918f1d" />

<img width="135" height="241" alt="Mesh Qual 2" src="https://github.com/user-attachments/assets/1df07bc5-6326-4cab-a64a-dfdf3d39ba4a" />

<img width="147" height="305" alt="Mesh Qual  3" src="https://github.com/user-attachments/assets/63716c69-9276-4802-8392-73013e079673" />

<img width="617" height="486" alt="Fixed Surfaces" src="https://github.com/user-attachments/assets/1f18c9cf-cfab-4a3b-b37d-49ae58e25e1b" />

Surfaces Fixed in FEA

<img width="696" height="320" alt="FEA forces" src="https://github.com/user-attachments/assets/ce2f25f5-8f61-43f6-9489-ecf9b6288573" />

Forces modeled in FEA


