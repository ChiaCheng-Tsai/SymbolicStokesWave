# SymbolicStokesWave

A Mathematica code for obtaining 7-th order Stokes waves in the Eulerian and Lagrangian descriptions

## Files description:

### Eulerian solutions:

Stokes_Euler.nb : the main code for solving Eulerian solutions

Stokes_Euler7.nb : the main code with 7-th order Eulerian solution

EulerPhi3 : result of the 3-rd order Eulerian solution by velocity potential formulation

EulerPhi5 : result of the 5-th order Eulerian solution by velocity potential formulation

EulerPhi7 : result of the 7-th order Eulerian solution by velocity potential formulation

EulerPsi3 : result of the 3-rd order Eulerian solution by Fenton's (1985) stream function formulation

EulerPsi5 : result of the 5-th order Eulerian solution by Fenton's (1985) stream function formulation

EulerPsi7 : result of the 7-th order Eulerian solution by Fenton's (1985) stream function formulation

FentonData.nb : code for producing coefficients of Fenton (1985)

FentonData : coefficients of Fenton (1985)

### Lagrangian solutions:

Stokes_Lagrange.nb : the main code for solving Lagrangian solutions

Stokes_Lagrange7.nb : the main code with 7-th order Lagrangian solution

Tool.nbd : include file for Stokes_Lagrange.nb

Lagrange3 : result of the 3-rd order Lagrangian solution by velocity potential formulation

Lagrange5 : result of the 5-th order Lagrangian solution by velocity potential formulation

Lagrange7 : result of the 7-th order Lagrangian solution by velocity potential formulation

LiouData.nb : code for producing coefficients of Liou (2005)

LiouData : coefficients of Liou (2005)

## References:

More details on the methods used in these scripts can be found in the following references:

* Chia-Cheng Tsai, Yang-Yih Chen, and Hung-Chu Hsu *[Automatic Euler—Lagrange Transformation of Nonlinear Progressive Waves in Water of Uniform Depth](https://www.tandfonline.com/doi/abs/10.1142/S0578563415500114)*. Coastal Engineering Journal, 57(3), 2015.

* Chia-Cheng Tsai, Jen-Yi Chang, Hung-Chu Hsu, and Yang-Yih Chen *[Using Symbolic Computing to Obtain Lagrange-Euler Solutions for Nonlinear Progressive Waves on a Uniform Current](https://www.jcronline.org/doi/abs/10.2112/JCOASTRES-D-18-00054.1)*. Journal of Coastal Research: 35(4), 872 – 883, 2019.

* Hung-Chu Hsu and Chia-Cheng Tsai *[Lagrangian approach to interfacial water waves with free surface](https://www.sciencedirect.com/science/article/pii/S0141118716302851)*. Applied Ocean Research, 59, 616-637, 2016.
