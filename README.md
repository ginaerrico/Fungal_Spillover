# Fungal_Spillover
This is a README text file for running “Code_Final”

To access and run the model, you will need R

Packages needed: deSolve, ReacTran, abc, abcrf, BioManager, ggplot2, dplyer, lime, keras, tensorflow, EBImage, tfdatasets, RColorBrewer, lattice, vegan

To create a randomized vector to simulate turbulence that will be used in a later model. #lines 18-25

Model0: baseline model with two plant species interacting with a resident pathogen in the absence of spillover. #lines 31-38

Model1: Testing the effects of introduced pathogen. Two plant species interacting with both the resident and introduced pathogen #lines 40-56

Model2: Testing the effects of introduced pathogen with the addition of wind. Two plant species interacting with both the resident and introduced pathogen #lines 58-&4

Model 3: Testing the effects of introduced pathogen with simulated turbulence, using the vector created in lines 18-25. Two plant species interacting with both the resident and introduced pathogen #lines 76-92

##To change wind speed (velocity) 
Wind & no velocity: v=0 #line 52
Wind & velocity: v=0.25 #line 70
Wind & turbulence: v=turb #line 88; (turb= turbulence vector #line 85)

Investigation of the effects of intraspecific competition on the coexistence outcome of model0. #lines 94-135

Extracting the specific population dynamics #lines 137-144

Summarizing and plotting the outcome of intraspecific competition on long-term coexistence: #lines 146-164 P1<=0.00001 P2>0.00001 Y1>0, P2 outcompetes P1. P1<=0.00001 P2>0.00001 Y1>0, P1 outcompetes P2. P1>0.00001 P2>0.00001 Y1>0, Coexistence. P1<=0.00001 P2<=0.00001 Y1<0, System crash.

**#lines 166-203**

Setting up the grid space #lines 209-210

Setting up initial parameters #lines 212-224

Investigation of the effects of intraspecific competition on the coexistence outcome of model1. #lines 226-257

Extracting the specific population dynamics #lines 259-265

Summarizing and plotting the outcome of intraspecific competition on long-term coexistence: #lines 268-292
P1<=0.00001 P2>0.00001 Y1>0, P2 outcompetes P1. P1<=0.00001 P2>0.00001 Y1>0, P1 outcompetes P2. P1>0.00001 P2>0.00001 Y1>0, Coexistence. P1<=0.00001 P2<=0.00001 Y1<0, System crash.

**lines 295-331**

Investigation of the effects of intraspecific competition on the coexistence outcome of model2. #lines 338-375

Extracting the specific population dynamics #lines 377-383

Summarizing and plotting the outcome of intraspecific competition on long-term coexistence: #lines 386-410
P1<=0.00001 P2>0.00001 Y1>0, P2 outcompetes P1. P1<=0.00001 P2>0.00001 Y1>0, P1 outcompetes P2. P1>0.00001 P2>0.00001 Y1>0, Coexistence. P1<=0.00001 P2<=0.00001 Y1<0, System crash.

**lines 413-449**

Investigation of the effects of intraspecific competition on the coexistence outcome of model3. #lines 456-493

Extracting the specific population dynamics #lines 495-501

Summarizing and plotting the outcome of intraspecific competition on long-term coexistence: #lines 504-528
P1<=0.00001 P2>0.00001 Y1>0, P2 outcompetes P1. P1<=0.00001 P2>0.00001 Y1>0, P1 outcompetes P2. P1>0.00001 P2>0.00001 Y1>0, Coexistence. P1<=0.00001 P2<=0.00001 Y1<0, System crash.

**lines 532-1020**
