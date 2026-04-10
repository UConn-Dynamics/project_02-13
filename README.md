Hello, I have uploaded the code from Julia, and notes from my little Ipad thing. They look huge on a computer but my screen is only like 5 inches, so I promise I do not write that big

My high-level description of what is needed to solve this problem, or any problem with constraints

Identify the DOF For this project, its a 2d model with 3 rigid bodies, so it needs 9 constraints
Write your constraint equations For this project, I wrote 9 very simple constraint equations. It would be possible to do this with less equations, where we use relationships like Professor Cooper outlined in the door problem. Relationship between global coordinates and Door Hinge = 2 constraints with 1 equation
Create the "jacobian" Professor Cooper did not use this term in his "drop". However, I did, so suck it. This is the matrix of the derivatives of the constraint equations with respect to each constraint/vector? idk the x1 y1 theta1 . . . This matrix describes how each variable changes in relation to each other variable.
Use a computer to solve this linear algebra problem to find qdot (how this thing moves)
Plot Plot Plot
