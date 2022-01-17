Disp "Lower bound: "
Prompt A
Disp "Upper bound: "
Prompt B
Disp "Intervals: "
Prompt C

B-A→R
R/C→L
L*.5→N
ClrDraw
AxesOn 

0→T

For(Z,A,B-.01,L)
Line(Z,0,Z,Y₁(Z+N))
Line(Z+L,0,Z+L,Y₁(Z+N))
Line(Z,Y₁(Z+N),Z+L,Y₁(Z+N))
Y₁(Z+N)*L→M
T+M→T
End

Disp T

