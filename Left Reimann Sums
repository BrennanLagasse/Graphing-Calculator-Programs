Disp "Lower bound: "
Prompt A
Disp "Upper bound: "
Prompt B
Disp "Intervals: "
Prompt C

B-A→R
R/C→L

ClrDraw
AxesOn 

0→T

For(Z,A,B-.01,L)
Line(Z,0,Z,Y₁(Z))
Line(Z+L,0,Z+L,Y₁(Z))
Line(Z,Y₁(Z),Z+L,Y₁(Z))
Y₁(Z)*L→M
T+M→T
End

Disp T

