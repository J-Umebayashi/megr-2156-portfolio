# A5 – Bracket Design

## Objective

Our assignment this week was to calculate dimensions for 5 different parts of a bracket using stress and deflection calculations. 

Here is the problem diagram given to us that we had to design the bracket around.

<img width="428" height="211" alt="Question diagram" src="https://github.com/user-attachments/assets/850e29ff-10d7-4f9c-814b-855c55c9744a" />

I chose to use 6061-T6 Aluminum for this design, with a tensile strength of 42ksi. My applied load was 600 lb, and all designs must have a safety factor of 4. 

## Feature A Stress Analysis
Attached is my work for the stress analysis on Feature 1.

<img width="1880" height="2507" alt="pg 1" src="https://github.com/user-attachments/assets/96700fa4-4822-420c-af3d-d28eb30ad05d" />

## Feature B Stress Analysis

Below is my work for the analysis of Feature B. I think I made a mistake or multiple with this analysis, as the dimension seems small to me.

<img width="1615" height="2153" alt="pg 2" src="https://github.com/user-attachments/assets/9fecb10b-e754-4e38-8254-b95b62eb2256" />

## Feature C Stress Analysis

<img width="1615" height="2153" alt="pg 2" src="https://github.com/user-attachments/assets/5f60c1f2-9e7b-4f94-96da-8b40536effc4" />

Here are my calculations for Feature 3. 

## Feature D Stress Analysis

<img width="1820" height="2427" alt="pg 3" src="https://github.com/user-attachments/assets/79d20f61-cc3c-44b1-b63f-b8417c501d18" />

This dimension seemed small to me, but it is not as egregious as the dimension for Feature B.

## Feature E Stress Analysis

<img width="1820" height="2427" alt="pg 3" src="https://github.com/user-attachments/assets/06ef0536-b03f-4ea3-bace-ea8363970694" />

##  Feature A Deflection Analysis

One assumption I forgot to record for all analysis is that the deflection angle is negligible.

Feature 1 Knowns:
L = ¾ in.
Max Deflection = 0.005 in.
F = 1200 lbs.

<img width="1602" height="2136" alt="pg 4" src="https://github.com/user-attachments/assets/cde95d01-87aa-4697-940c-4f34011e11f5" />

## Feature B Deflection Analysis

Knowns:
L = 1.25 in.
E = 10,000 ksi
F = 1200 lbs.

<img width="1602" height="2136" alt="pg 4" src="https://github.com/user-attachments/assets/946e0dcb-d789-4bab-ac81-580900f512b5" />

I did not have time to go back and fix this calculation, I realized I didn’t fix this as I am looking back through this. The dimension I calculated seems very small.

## Feature C Deflection Analysis

Knowns:

Width = 2.49 in.
E = 10,000 ksi
Assumptions:
Treat as a simply supported beam

<img width="1722" height="2296" alt="pg 5" src="https://github.com/user-attachments/assets/069eb56d-7996-4e1b-b2c6-371a18485ee9" />

## Feature D Deflection Analysis

<img width="1722" height="2296" alt="pg 5" src="https://github.com/user-attachments/assets/b61b816f-e311-439c-a9fe-b5ce47788fac" />

## Feature E Deflection Analysis

<img width="1621" height="2161" alt="pg 6" src="https://github.com/user-attachments/assets/90f7badf-c6b7-4844-8da9-a687f9d49c70" />

## Stress Analysis Drawing

<img width="1800" height="2400" alt="pg 7" src="https://github.com/user-attachments/assets/ea54e2d6-33c0-4500-9cdd-cd55eb0ac57b" />

## Deflection Analysis Drawing

<img width="1670" height="2227" alt="pg 8" src="https://github.com/user-attachments/assets/2f2134ad-905b-4062-9238-530118dafbbe" />

## Lessons Learned

For Feature B, the dimension calculated from the Stress Analysis governed the dimensions of the part. The stress analysis calculated a thickness of 0.0914 in, while the deflection analysis calculated a thickness of 0.0314 in. The stress dimension was almost three times larger. The feature needs the larger dimension to prevent failure.  

I am not aware of a propagation error that continued downstream through my math. The only big problem I have in my work is with the Feature B calculations I highlighted earlier. I didn’t have a way to check myself as I worked, so that may be hiding the errors.

I assumed a tensile strength of 42 ksi. If this strength was lessened, my dimensions would not be sufficient to hold up the load, and if this strength was greater, then my bracket would seem overbuilt.

I realized I wasn’t consistent with my solving methods on paper in this assignment, and that is something I definitely need to clean up for presentation and to keep myself more organized. I also think I constrained some of my free body diagrams incorrectly, which can lead to errors.



