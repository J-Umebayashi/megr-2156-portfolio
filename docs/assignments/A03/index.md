# A3 – [Topic]

## Objective
The assignment for this week was to design a bar using two analysis types, axial deflection and finite element analysis (FEA). 
Here are the design constraints for this assignment:

Max Axial Deflection: 0.009”

- A directly applied load between 300 - 500 lbf. 

- Bar must be made of aluminum with a Young’s Modulus value between 8.5-11 x 10-6 psi.

- Bar must have a circular cross-sectional area.

## Decide

I chose to model my bar with 6061-T6 aluminum, which as a Young’s Modulus value of 10 x 106 psi. The bar has a diameter of 1.5 inches, and a cross-sectional area of 1.767 in2. The image below shows the direct tensions elongation equation and the hand calculations to double check the Solidworks equations and to ensure I was plugging in the correct variables and had the correct algebra for finding the length.

<img width="1732" height="2309" alt="20260905_181224" src="https://github.com/user-attachments/assets/30fbab1b-849a-4a4c-8059-ad895b1e8e00" />

The bar length I calculated was 454.371 in., I was skeptical of this value at first due to the length, but after checking my calculations and talking to Dr. Fagan, I am confident that I used these equations correctly. 

SOLIDWORKS

After I finished my hand calculations, I moved over to Solidworks. Same as last week, I am using Solidworks 2025. I began my model by assigning and defining all the global variables and equations I had from my hand calculations. 


<img width="652" height="294" alt="{B25DA439-0019-4C1A-BB4E-4657597AE28E}" src="https://github.com/user-attachments/assets/e66842bd-eeda-4197-ba85-6634caf46765" />

I made sure to use the same variables I used on paper to ensure I didn’t flip or change variables by accident. The calculations on Solidworks came out to about the exact same number I got on paper, with a slight difference in rounding being the only difference at all. Once the equations were finished, I modeled and extruded the bar. Below is the sketch of the bar, which was then extruded using the global values shown above.

<img width="997" height="534" alt="Sketch" src="https://github.com/user-attachments/assets/0c0b8925-04dc-41b4-ad8b-021fc4a4c45d" />

FINITE ELEMENT ANALYSIS

After modeling, I began to set up the FEA. I fixtured one side of the bar, and applied the 350lbf to the other side, just like the diagram on the assignment sheet. 

<img width="783" height="425" alt="{292E4F38-5CDB-4CB1-8818-95A969E73A76}" src="https://github.com/user-attachments/assets/a8350f6c-610b-4e0e-9729-231ea8bcb26f" />

<img width="896" height="498" alt="Fixtured side" src="https://github.com/user-attachments/assets/f4cd0e5c-88ec-4693-bc7b-a093d1e36be7" />

After assigning fixtures, forces, and creating a mesh on the body, I began running the studies. Below are all the maps that were generated from the FEA, with the scales included. 

<img width="967" height="384" alt="von Mises standard" src="https://github.com/user-attachments/assets/ef0abc32-c768-4e67-a733-585ec5a39fc7" />




## Communicate

