# OBE-Solver
This is the python and Julia based optical Bloch equation solver that was used in CaH Sisyphus cooling paper.

## If you are new to OBE
You can acquire the basic knowledge quickly from Konrad Wenz's thesis ("Nuclear Schiff Moment Search in Thallium Fluoride Molecular Beam: Rotational Cooling" Chapter 4) and his Github (https://github.com/kwenz/OBE-solver). You can also check out Dr. 
Olivier Grasdijk's Github (https://github.com/ograsdijk/optical-bloch) where my code is developed based on.

## When you use this code for the first time
I'd highly recommend you to start from the file "3+1 toy model system.ipynb". There I put step by step comments to explain what is the purpose of this section of code. You can choose to not use Julia for the first time using it.

When you are familiar with the basic structure and want to use more complicated hamiltonian and calculate the force/density matrix evolution, I would recommend you to then follow the file "3+1 toy system with force calculation.ipynb". There I have complete calculation for a toy model.

# Complete picture
If we want to move on to a more complicated system, you can either play with 3+3 or 5+3 systems, or you can go to "CaH Sisyphus calculation example code.ipynb" directly, where the code was used to generate the plots for the CaH Sisyphus cooling paper. It has the most complete picture of my calculations, and if you have any question, feel free to contact me at qs2207 at columbia dot edu. 

If you want to use it to other systems, such as 2+2 systems but you do not have the rabi matrix elements, please refer to konrad's Github (https://github.com/kwenz/OBE-solver) or my another repository (https://github.com/QiSun97/Rabi_Matrix_Elements_Calculator) where we used Matlab to calculate them. The rabi matrix elements will be not only used in filling off-diagonal hamiltonian, but also used to calculate the branching ratios and the dissipator.
