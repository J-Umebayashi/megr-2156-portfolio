# A3 – [Topic]

## Objective
The assignment for this week was to design a bar using two analysis types, axial deflection and finite element analysis (FEA). 
Here are the design constraints for this assignment:

Max Axial Deflection: 0.009”

- A directly applied load between 300 - 500 lbf. 

- Bar must be made of aluminum with a Young’s Modulus value between 8.5-11 x 10-6 psi.

- Bar must have a circular cross-sectional area.

## Analyze

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
This is the Von Mises map and also shows max stress.  

<img width="821" height="458" alt="Displacement standard" src="https://github.com/user-attachments/assets/f35ab5a4-81fd-453a-acb6-e81bf57adfda" />
This is the deflection map.

The max stress according to the FEA studies is 207.2 psi, which converts to 0.2072 ksi. This is well under the 40 ksi limit for Aluminum strength. A quick calculation gives the safety factor.
40/0.2072  = 193.050 
The safety factor of this bar is approximately 193. 

DESIGN REFLECTION

<img width="3000" height="836" alt="20260907_151558" src="https://github.com/user-attachments/assets/f46c6cdb-d9de-47a3-bcbd-e5bed1674e54" />

These are the hand calculations I performed between the FEA deflection value and the calculated deflection value from the axial deflection equation and the values I used to determine the length of the beam. The two values have a very slight difference, only 0.2%. I expected these values to agree due to the same equations being used in Solidworks and on paper. Since this bar is experiencing a simple axial deflection, there isn’t much difference between paper and the computer. I think the 0.2% difference comes from Solidworks rounding numbers more than I did on paper.

I found the stress concentration value to be 3. This was found on page 216 of the Machinery’s Handbook. The max stress of the bar going away from the hole is 207.2psi. Multiplying this value by the concentration value gives a peak stress of 621.6psi. The hole decreases the bars’ safety factor from 193 to approximately 64. This will still pass the safety factor.

<img width="1320" height="1760" alt="20260907_161148" src="https://github.com/user-attachments/assets/237ef30b-b375-4697-9ed8-58576b88defd" />

## Communicate

LESSONS LEARNED

There weren’t any massive mistakes made throughout this project. Most of my errors came from algebra errors; just causing me to redo some equations. I began this project earlier than the last one, which allowed me more time overall to double check my work and ensure I was on the right path with this project. I was skeptical of my bar calculations, but after double checking with Dr. Fagan, I knew I was good. My planning and documentation were a lot better than the second project because I was more aware of them and developed better processes of having a more thorough documentation. 
I spent about 4.5 hours on this. I broke this up into chunks, which may have slowed my progress, but I feel overall my efficiency was acceptable. 

APPENDIX

Bar Solidworks file:

[Bar Solidworks file](https://drive.google.com/file/d/1cbJgsDErlTogaHCNnKYsVD76j8toZPoy/view?usp=sharing)






