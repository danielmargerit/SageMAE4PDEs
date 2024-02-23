# SageMAE4PDEs

## Title
MAE (Matched Asymptotic Expansion) for PDEs (Partial Differential Equations) aided by SageMath free open-source mathematics software system

## Interest of using a symbolic calculator in MAE for PDEs
We are interested in using the Matched Asymptotic Expansion method to provide solutions of Partial Differential Equations. This often leads to difficult calculations in which humans can make mistakes when deriving those calculations on a sheet of paper.

Also errors or typos can come when we copy the formula from the sheet of paper to the paper to be published.

So as to prevent such kinds of mistakes or typos we can use a symbolic calculator. It can help to cross check any error and can provide an already formula in the latex form to be integrated in the paper to be published.

The symbolic calculator may also help to derive those calculations quickly. It may allow us to explore more derivations so as to find a shorter derivation.

It can also allow us to find higher asymptotics that couldn't be achieved during the whole life of a human.

It can help to check the validity of the final asymptotic result by replacing it in the initial equations.

## Examples of SageMath notebooks to do MAE for PDEs
We provide here examples of using the SageMath tool (the free open-source mathematics software system) to derive those calculations.
### Slender Vortex Filament motion
- **Slender vortex filaments in the Boussinesq Approximation, Marie Rodal, Daniel Margerit, Rupert Klein, submitted to Physics of Fluids, [[pdf preprint (to be added)]](slender_vf_in_BA)**
	- vortex filament derivation [[ipynb]](https://github.com/danielmargerit/SageMAE4PDEs/blob/main/Notebooks/vortex_dynamics/vortex_nb_CT.ipynb) : 
		  local curvilinear operators, asymptotic expansions in those operators, simplification of the equations at each orders (symmetrical part)
	- vortex filament equations [[ipynb]](https://github.com/danielmargerit/SageMAE4PDEs/Notebooks/vortex_dynamics/vortex_nb_CT-Summary.ipynb) : the outcome equations at each orders
https://

### Other examples (To be done)

## Old first examples of using symbolic calculators in MAE for PDEs (with Maple)
Symbolic calculators have already been used in different researches.

### Slender Vortex Filament motion
- The Complete First Order Expansion of a Slender Vortex Ring, D. Margerit, J-P. Brancher, IUTAM Symposium on Dynamics of Slender Vortices pp 45–53, held in Aachen, Germany, 31 August – 3 September 1997 : [[pdf]](https://danielmargerit.github.io/docs/papers/iutam_slender_vortex_dm.pdf)
the authors used Maple to rederive the Callegari and Ting equation of motion and find the next Order
- D. Margerit, Dynamique et mouvement des filaments et des anneaux tourbillons de faible épaisseur, Thèse de doctorat de troisième cycle à l’INPL de Nancy, 6 Nov. 1997, [[pdf]](https://danielmargerit.github.io/docs/papers/PhDThesis_D.Margerit_1997INPL132N.pdf)
See chapter 12
	- MAE for Biot and Savart (to be added soon)[[maple notebook]](Biot1) : outer matched asymptotic expansion in Biot and Savart integral law to find the outer expansion of the outer velocity near the filament
	- MAE for desingularised cut of integral (to be added soon)[[maple notebook]](Cut) : matched asymptotic expansion in Biot and Savart desingularised integral (based on a cut off) to find the outer expansion of the velocity when the cut off parameter is small 
	- MAE for Biot and Savart (to be added soon)[[maple notebook]](Biot2) : inner matched asymptotic expansion in Biot and Savart integral law with core thickness to find the expansion of the inner velocity of the filament, the value of this inner velocity on the filament centerline, the value of this velocity at infinity
	- MAE for the Navier Stokes equations written on local curvilinear coordinates (to be added soon)[[maple notebook]](Curviligne) : the different order of the Navier Stokes equations, solving those equations
	- MAE for the Navier Stokes equations written on local curvilinear coordinates (to be added soon)[[maple notebook]](Vorticity) : the different order of the vorticity equations

Those Maple scripts were not provided with the published papers mainly because they were correct but too complexe and surely not with the level of quality we would like to have.
Using commercial tools did not allow us in the past to achieve simplification of notebooks as we would like. With an open source tool as SageMath we no longer have this limitation and we may think that we could now achieve this goal of simplification.


### Scroll waves study
- Selection of twisted scroll waves in three-dimensional excitable media, D. Margerit, D. Barkley, Phys. Rev. Lett. 86, 175-178, 2001 : [[pdf]](https://danielmargerit.github.io/docs/papers/prl.pdf)
the authors used Maple to find the next Order
Associated Maple files (to come)

### Other papers (To be investigated)
xxxx

Those  Maple scripts were not provided with the published papers mainly because they were correct but too complexe and surely not with the level of quality we would like to have.
Using commercial tools did not allow us in the past to achieve simplification of notebooks as we would like. With an open source tool as SageMath we no longer have this limitation and we may think that we could now achieve this goal of simplification.


## Toward an improvement of using SageMath to do MAE for PDEs

We would be happy to improve those derivations aided by the SageMath calculators :
- by better using capabilities of SageMath
- by improving the packages of SageMath to provide an efficient package to perform MAE (Matched Asymptotic Expansion) for PDEs (Partial Differential Equations.

The goal would be that the code to perform such calculations become more robust and provide a much simpler notebook than we have reached today. 
We would like that the community having to perform such MAE calculations can use it more easily.

## How to achieve this ?
So we can use the provided examples (and maybe others to come):
- to define the underlying requirements (or needed features)
- to check which capabilities may be already available in SageMath and use them to simplify the current notebooks
- to describe the requirements that are not covered or partially covered and specify the associated needed capabilities to be developed
- then do the associated SageMath improvements (if needed)
- finally simplify the provided notebook(s)

## Bibliography (To be investigated)
xxxx