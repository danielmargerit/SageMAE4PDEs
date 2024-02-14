# SageMAE4PDEs

## Title
MAE (Matched Asymptotic Expansion) for PDEs (Partial Differential Equations) aided by SageMath free open-source mathematics software system

## Gooal
We are interested in using the Matched Asymptotic Expansion method to provide solutions of Partial Differential Equations. This often leads to difficult calculations in which humans can make mistakes when deriving those calculations on a sheet of paper.

Also errors or typos can come when we copy the formula from the sheet of paper to the paper to be published.

So as to prevent such kinds of mistakes or typos we can use a symbolic calculator. It can help to cross check any error and can provide an already formula in the latex form to be integrated in the paper to be published.

The symbolic calculator may also help to derive those calculations quickly. It may allow us to explore more derivations so as to find a shorter derivation.

It can also allow to find higher asymptotics that couldn't be achieved during the whole life of a human.

It can help to check the validity of the final asymptotic result by replacing it in the initial equations.

Symbolic calculators have already been used in different researches. For instance:
- in vortex dynamic to derive the equation of motion of a slender vortex filament
	- The Complete First Order Expansion of a Slender Vortex Ring, D. Margerit, J-P. Brancher,  IUTAM Symposium on Dynamics of Slender Vortices pp 45–53, held in Aachen, Germany, 31 August – 3 September 1997 : the authors used Maple to rederive the Callegari and Ting equation of motion and find the next Order
	- Slender vortex filaments in the Boussinesq Approximation, Marie Rodal, Daniel Margerit, Rupert Klein, preprint, february 2024 : the authors used SageMath to cross check the derivation and extension to buoyancy of the Callegari and Ting equation of motion
- in scroll waves study
	- Selection of twisted scroll waves in three-dimensional excitable media, D. Margerit, D. Barkley, Phys. Rev. Lett. 86, 175-178, 2001 : the authors used Maple to find the next Order

We provide here examples of using the SageMath (the free open-source mathematics software system) to derive those calculations :
- our first example is the SageMath notebooks used in the paper : Slender vortex filaments in the Boussinesq Approximation, Marie Rodal, Daniel Margerit, Rupert Klein,
- we may provide other examples: for instance based on other previously cited papers


We would be happy to improve those derivations aided by symbolic calculators :
- by better using capabilities of those calculators
- by improving the packages of those calculators to provide an efficient package to perform MAE (Matched Asymptotic Expansion) for PDEs (Partial Differential Equations.
The goal would be that the code to perform such calculations become more robust and provide a much simpler notebook as what we have reached today such that the community having to perform such calculations can use it more easily.

So we can use the provided examples :
- to define the underlying requirements (or needed features)
- to check which capabilities may be already available in SageMath and use them to simplify the current notebooks
- to describe the requirements that are not covered or partially covered and specify the associated needed capabilities to be developed
- then do the associated SageMath improvements (if needed)
- finally simplify the notebook that was provided as an example