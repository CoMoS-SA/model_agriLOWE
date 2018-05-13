# agriLOWE
This repository contains all the features and instructions necessary to reproduce the agriLOWE ABM model. The model encompasses a spatial-based economy with an ecology of N farmers and 3 different types of land. Technological progress as well as shocks deriving from the interactions with the climate are modelled. 

The simulation aims at addressing these two open issues: is it possible to assess the climate change impacts to the agricultural sector in different technologically – developed countries, utilizing a global model? Further, is low technological change in the agricultural sector a bottleneck for development and climate change mitigation?

# Model's main components
a) Ecology of N farmers (no exit & no entry); 

b) 3 types of land: forestry, low-yield land (characterized by low fertility and intrinsic low productivity of the land) and high-yield land (where the fertility of the ground and the related productivity are instead higher);

b) Production = min {alphaL, gammaS, thetaK} with alpha=productivity of labour embodied in the machines;
                                                  gamma=productivity of land;
                                                  theta=productivity of capital;
                                                  
c)Each farmer produce an homogenous bundle of food and the market is perfectly competitive;

d) Demand is increasing at a fix rate over time: D=D(t-)(1+*d*)

e) 

# Model's Feature
*Code Language* : R, C++ (under development)

*Compile* : R no need, C++ uses CMake

*Inputs*: 21 + a spatial matrix

*Outputs*: 14 time series of interest

# Code structure
Load functions
Data: import parameter set; 
