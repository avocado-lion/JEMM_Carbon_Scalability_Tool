# JEMM_Carbon_Scalibility_Tool
This repository's purpose is to establish public access to the JEMM Carbon Scalibility Tool Version 9 python code.

# About 
JEMM Carbon is a Simon Fraser University (SFU) Sustainable Energy Engineering (SEE) student capstone team located in Vancouver, Canada.
Over 8 months in 2024-25, JEMM Carbon developed an innovative carbon capture solution for buildings HVAC&R systems' CO2 emissions for the 2025 Setty Family Applied Engineering Challenge. 
The Scalability Tool is one component of this design. 
Building HVAC&R systems vary in size, flow rates, and outlet compositions. 
Consequently, the Scalibility Tool was developped to simulate CO2 adsorption in the JEMM Carbon designed adsorber bed under different conditions. 
The tool then generates recommendations for adsorber bed sizing (Small, Medium, or Large) and configuration (X units in series and/or parallel) based on multiple simulations.

# How it Works
The tool first calculates a breakthrough curve for a Small adsorber bed based on a building’s HVAC&R parameters. 
It uses a material isotherm equation, the Linear Driving Force (LDF) model, a mass balance equation, and two discretization methods—Explicit Euler and Upwind Differencing Scheme for Convection—to compute CO2 concentration and adsorption at each spatial point of the given adsorber bed over time. 
The results then inform sizing and arrangement optimization.
