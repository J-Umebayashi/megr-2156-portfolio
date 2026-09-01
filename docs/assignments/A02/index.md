# A2 – Truss Stress Analysis

## Objective
For this assignment, I was tasked with designing a 2-D planar truss. The image below shows some of the parameters assigned.

<img width="350" height="180" alt="{A5125610-F9C3-474D-8E0A-BDB85BDB328E}" src="https://github.com/user-attachments/assets/39cb4bb8-64b9-476e-9e04-75f2db54fd79" />

The distance, a, is 0.4m, b is 0.3m. The two forces labeled P are 25kN, point A is a pin connection, and point B is a roller support. The beams of the truss had to be made from A500 structural steel and the cross-sections had to be equal throughout the beam.

## Decide
INTRODUCTION

I chose a 7 member design, this was the most familiar design I could think of while keeping the truss symmetrical. This isn't the lightist option, but it was the simpliest with geometry and trigonometry.

<img width="1713" height="522" alt="Truss sketch" src="https://github.com/user-attachments/assets/9c5076d4-8403-41a1-9f5a-857ad7953b2e" />

## Analyze
SOLVING FOR FORCES

The first step was to solve the global equilibrium of the truss, and then find the forces of the individual members within the truss. I performed all of these calculations symbolically first, before plugging in numerical values. Below are the rest of the joint calculations and the numerical solving.

<img width="1713" height="2284" alt="20260831_122519" src="https://github.com/user-attachments/assets/d90b0e86-5126-4b98-9d8e-97b68f4434b2" />

<img width="1436" height="1915" alt="20260830_232146" src="https://github.com/user-attachments/assets/9eb4f032-01bd-475b-a029-548d0928cf5a" />

<img width="1484" height="1979" alt="20260830_232416" src="https://github.com/user-attachments/assets/c1ac1689-ea5c-441d-934a-9d70cd0d7bd5" />

After finding the reaction forces and internal forces of the beam, I moved on to finding the cross-section of the beam. I am currently taking Solids, so this section proved to be very difficult for me. The truss needed a safety factor of 3.5 and all members had to have the same cross-sectional area. I used the internet to find the density and yield strength of A500 steel.

<img width="1756" height="2342" alt="20260831_095811" src="https://github.com/user-attachments/assets/ca535c1a-1812-4cff-b95e-f9e7b37b111d" />

<img width="1898" height="2531" alt="20260831_100418" src="https://github.com/user-attachments/assets/ccd9e19c-a7c6-4423-a2c0-dfae4b7844a5" />

The photos above shows my calculations for the pin cross section and diameter as well. The pins in the truss are in single shear, and needed a safety factor of 4. All pins had to be the exact same size. 

CAD MODELING

I used Solidworks 2025 to model my truss and pin due to my familiarity with the software and I already have my license and account set up on my personal laptop. 

<img width="1191" height="673" alt="{DA69EDB6-BA73-4741-9C77-6F5F9E4A7B5D}" src="https://github.com/user-attachments/assets/e1011608-1e06-4686-ae92-8a325ad0ace9" />

Shown above is my truss with dimensions in Solidworks. I first established the top and bottom lengths, constrained them, then drew the inner members of the truss. I used the extrude cut tool to cut the pin holes into the truss, and I used reference geometry to ensure they were all square with the beam and in line with each other. After sketching and extruding the truss, I assigned a material to the truss. Solidworks does not have A500 steel listed in their system, so I decided to use 1035 Steel (SS) since it has the closest yield strength I could find compared to A500. 

<img width="1153" height="671" alt="{F9C76C4F-56AA-437E-AEE8-520E829FE60B}" src="https://github.com/user-attachments/assets/29c2187a-18d8-4126-8899-600b14cc2250" />

<img width="703" height="530" alt="{DE7FF991-B263-4ABC-8495-6D3E606D9C7B}" src="https://github.com/user-attachments/assets/e19222b5-c6ca-49f0-8422-d09d1d170ef7" />

My truss weighs 12.14kg according to the solidworks model, my calculations had the truss weight around 6kg, so there is clearly an error in my hand calculations that needs to be addressed if I were to do this project again. 

For the pin I used cold-rolled 1020 steel. I could not find tool-hardened steel in Solidworks, and I recently learned that cold-rolled steel means that the steel has been hardened, which would act the most like tool-hardened steel from my understanding.

<img width="827" height="568" alt="{359E14B8-13A4-4455-9E17-7EB32DCC37E1}" src="https://github.com/user-attachments/assets/c9fe8454-d378-4e5c-add4-94ef6f211e68" />

Here is my pin modeled in Solidworks to the dimensions I hand-calculated. 

<img width="335" height="299" alt="{1BFC6337-830B-432E-A3E7-FAA01AD7C9A1}" src="https://github.com/user-attachments/assets/80f4b777-4cab-4b63-b89b-39297b25b535" />

MODEL ANALYSIS

After modeling the parts, I began to run FEA on the truss. I used a fixed geometry fixture at points A and B, and I added the forces at pins C and D, using planes within the model to add a direction to each force to mirror the assignment. 

The truss FEA results showed that my design’s lowest safety factor was a 2. Unfortunately, this does not meet the assignment goal of the whole truss having a safety factor of 3.5. 

<img width="1187" height="714" alt="Use this FEA" src="https://github.com/user-attachments/assets/680deb94-a455-4c46-906a-fbe44220dd92" />

The troublesome area is right around the vertex of the middle elements. If I had more time, I would re-work my cross-sectional area calculations to make sure my truss thickness is correct, as I believe that is my first problem. I don’t fully understand the mistakes I made, I may have taken the wrong approach to finding the cross-sectional area, or it could have been a basic algebra error. I did not have enough time to thoroughly go back through my work and fix the mistake. I found doubling the cross-section in Solidworks gave me the safety factor required, but obviously my hand-calculations do not reflect those values. 

My Pin FEA showed a safety factor well below the required amount for the assignment. I think the material difference may be a part of the problem; I also believe my fixturing is a problem, as I used fixed geometry on both ends. 

<img width="1054" height="438" alt="{8AF50881-4B29-406C-AF49-5E23B23FF335}" src="https://github.com/user-attachments/assets/72857820-014f-452d-91a5-d03ca25de00c" />

## Communicate

CONCLUSIONS AND LESSONS LEARNED

This project took me 12 hours to complete. I believe I could have reduced the time to complete this project if I had better planned out the assignment. I should have prioritized certain parts of the assignment and scheduled my work for it accordingly. Also having other assignments and commitments spread out my time on this project. I learned that I need to be more thorough and careful with my algebra. I made multiple mistakes in my calculations that I didn’t notice until I was well past the point where it would be easy to fix them. Organizing my work better would also help me, making it easier for me to assign the important values I need later in the project. 
I learned the importance of planning and consistency in units and rounding throughout this assignment. I had multiple instances where values changed because of premature rounding in earlier equations or incorrect unit conversions. If I had a better planned strategy of how I was going to attack this assignment, I believe my work would have been more accurate and mistakes would have been way easier to minimize and catch before they caused bigger problems. This project really told me that I need to schedule more time for these projects as the semester continues.

APPENDIX

Truss File Download: https://drive.google.com/file/d/1x7DGgrM8wVxA5SEGqm4hYjT7EQTpEDFW/view?usp=sharing

Truss Pin File Download:
https://drive.google.com/file/d/1I-RXwCPJiSEpVLcCKOLhFEUAz4UpNqK-/view?usp=sharing
