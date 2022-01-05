# ProjectDDC
## Synthesis of control policies from demonstrations for fully driverless trains
Authors: 
* Francesco Avallone <f.avallone20@studenti.unisa.it>
* Martina Lamberti   <m.lamberti61@studenti.unisa.it>
* Lorenzo Pagliara   <l.pagliara5@studenti.unisa.it>

### Context. 
An appealing framework to design controllers from data is that of using example datasets. This
learning from demonstrations approach involves learning actions by observing an expert. Situations where the
synthesis of control policies from examples is of interest naturally arise in the applications from e.g. autonomous
urban driving, where one is often interested in designing policies from driving examples of multiple drivers, while
ensuring that the control (e.g. speed, acceleration) signal fulfills certain properties with some acceptable/design
probability level. In this context, students will design a control algorithm to enable a driverless train to take
advantage of the opportunities offered by expert (or demonstration) data

### Functions description. 
A key challenge in today’s intelligent transportation systems is that of replacing
humans with autonomous agents in safety-critical applications. To do so, an approach leverages the design of
algorithms from experts: the idea is to replace human drivers with control algorithms that extract best-practices
from the drivers. The algorithm that will be designed within this project needs to fulfill the following high-level
requirements:
* the control policy needs to be such that, given an example dataset, makes the behavior of the closed-loop
system similar to the one from the experts;
* the policy must be optimal and the algorithm needs to run smoothly, allowing for little computation
overhead.

### Specific tasks. 
In order to successfully complete the project, the following work-packages (WP) need to be
tackled. Note that some of the WPs are marked as optional.

#### WP1: 
Analyze and understand the supporting code on elearning. Define the key elements of the problem.
These elements include (but are not limited to): data-sources (if any), desired/target behavior, decision
variables. Define the problem statement and discuss the techniques you plan to use (and why);

#### WP2: 
Implement the greedy version of the algorithm (i.e. looking only one-step ahead);

#### WP3:
Obtain numerical simulations to illustrate the results and discuss performance, limitations and possible
further improvements; 


#### WP4 - optional: 
Implement a receding horizon version of the algorithm;

#### WP5 - optional:
Implement routines that allow to take as input non-Gaussian probability functions; 

#### WP6:
Implement any other algorithm and benchmark the results.

#### Note:
The jupyter notebook (supporting_code.ipynb) includes a number of tasks. These need to be solved in order to complete the WPs. By implementing, developing,.... it is meant that the corresponding task needs to be fully executed and the code (if any) fully working.

## Implementation
The user can see the mandatory WPs and the optional WP4 in the file "Project_script.ipynb".

In order to implement the optional WP5 the authors have defined another file "WP5.ipynb".

In addition, two other files have been defined for WP6("Regression.ipynb" and "WP6.ipynb") in order to suggest a possible solution with the do-mpc tool.