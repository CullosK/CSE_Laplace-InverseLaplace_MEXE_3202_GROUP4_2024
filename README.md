# G4_MATLAB-ACTIVIES
This is an Activity. Group 4 CSE activity.

Assignment 1

Inverse Laplace 

[Uploading ASS1_LAPLACE_TRANSFORM.m…]()%%clc
syms t

%% ASSIGNMENT 1

%LAPLACE TRANSFORM

%1
f1 = 3 - exp(-3*t) + 5*sin(2*t)
F1 = laplace(f1)
pretty(F1)

%2
f2 = 3 + 12*t + 42*t^3 - 3*exp(2*t)
F2 = laplace(f2)
pretty(F2)

%3
f3 = (t + 1) * (t + 2)
F3 = laplace(f3)
pretty(F3)

%% Inverse Laplace
syms s

%1 
F4 = (8-3*s + s^2) / (s^3)
f4 = ilaplace(F4)
pretty(f4)

%2
F5 = 5 / (s-2) - (4*s) / (s^2 + 9)
f5 = ilaplace(F5)
pretty(f5)

%3 
F6 = 7 / (s^2 + 6)
f6 = ilaplace(F6)
pretty(f6)




