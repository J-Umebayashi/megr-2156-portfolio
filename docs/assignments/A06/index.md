# A6 – Bracket Drawing

## Introduction
The assignment for this week is a continuation of the assignment from last week. The task this week is to parametrically dimension a Solidworks model of the bracket created. For reference, here is the model diagram from last week that the assignment is based around.

<img width="428" height="211" alt="Question diagram" src="https://github.com/user-attachments/assets/c36fa208-7f1f-4328-9d32-1b306e37b051" />

## Parametric Design

I will be using the dimensions I calculated using the stress equations, I will list them here for documentation.

Feature A:
Length: ¾ in.
Diameter: 0.995 in.

Feature B:
Length: 1 ¼ in.
Width: 0.995 in.
Thickness: 0.0914 in. 

Feature C:
Length: 1 in.
Width: 2.496 in.
Height: 0.828 in.

Feature D:
Length: 1 in.
Width: 0.15 in.
Height: 1.499 in.

Feature E:
Length: 1 in
Width: 0.999 in.
Height: 0.585 in.

<img width="600" height="395" alt="Parametric Values" src="https://github.com/user-attachments/assets/7c1ef8a8-bc54-4bd9-becd-638abc10c70f" />

Here are all the values put into the global variables in my Solidworks file.

<img width="543" height="549" alt="Model Screenshot" src="https://github.com/user-attachments/assets/d43f15ee-2b53-4682-a70f-c4163a3a13e1" />

## Drawing

<img width="1637" height="810" alt="Bracket Drawing jpg" src="https://github.com/user-attachments/assets/b59ae1fe-688f-455f-b422-a46186353bfd" />

Here is the drawing from my Solidworks model. I will link this drawing and the Solidworks file down in the Appendix. 
## Reflections

The stiffness equation in the last assignment defined the thickness of Feature B in my model. I did not relate the dimension to a CAD variable in my model. I was not aware this was a requirement when I was creating my CAD model and adding my global dimensions. If I had more time I would go back and add the equations with just variables into the equation manager, then solve for my dimensions by plugging them into the equation.

The tolerance I assigned to feature E was 0.005. This fit is a friction fit between the top of the T-bracket and my bracket. It needs to be able to slide off the t-bracket, but still hold the bracket in place when mounted. This fit needs to be exact to achieve this. The thickness of feature C has a tolerance of 0.02 in. This tolerance is acceptable due to this feature not being a key factor in holding the bracket in place on the T-bracket. 

I struggled at first creating the drawing. This was my first time creating an engineering drawing from Solidworks, and it took me a while to understand what I was doing. Assigning and defining the tolerances was also challenging. I found I couldn’t get the correct number of decimal places to display on my dimensions and the global equations in Solidworks kept rounding my dimensions. I’m sure there is a feature I’m overlooking, but I am not sure how to currently resolve this issue. This assignment took me about 6 hours to complete. I have a better fundamental understanding of tolerances and fits now. 

## Appendix

[Bracket CAD Model](https://drive.google.com/file/d/1O96cCDnLjjbx4GAkwktWwXFytYgAuhEN/view?usp=drive_link)

[Bracket Drawing](https://drive.google.com/file/d/17lk_BuCntjR_icL_sptR8Prdbux2qswJ/view?usp=drive_link)

