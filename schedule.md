# Schedule

## Friday


Join us for a buffet dinner, 6:30-9pm in ICCS X860 (the 8th-floor
lounge of the UBC [Department of Computer Science](cs.ubc.ca) (see [Google maps](https://maps.google.com/maps/ms?msid=206935814122343764231.00046d9d1f78b26a3814c&msa=0))

- Cost: $20 for faculty and guests; $12 for students.
- Please make sure to [registration.html register] if you plan to attend.

## Saturday


| Time          | Speaker           |
|---------------|-------------------|
|  8:30 -  9:00	| Breakfast         |
|  9:00 -  9:40	| [John Duchi](schedule.md#John_Duchi)        |
|  9:40 - 10:20	| [Zaid Harchoui](schedule.md#Zaid_Harchoui)     |
| 10:20 - 10:40	| Break             |
| 10:40 - 11:20	| [Sedi Bartz](schedule.md#Sedi_Bartz)        |
| 11:20 - 12:00	| [Zhaosong Lu](schedule.md#Zhaosong_Lu)       |
| 12:00 - 13:30	| Lunch             |
| 13:30 - 14:10	| [Yin Tat Lee](schedule.md#Yin_Tat_Lee)       |
| 14:10 - 14:50	| Student Talks     |
| 14:50 - 15:10	| Break             |
| 15:10 - 15:40	|[Terry Rockafellar](schedule.md#Terry_Rockafellar) |
| 15:40 - 16:00	| Closing remarks   |

## John Duchi

Department of Computer Science, Stanford University

### Local Minimax Complexity of Stochastic Convex Optimization

We extend the traditional worst-case, minimax analysis of stochastic convex optimization by introducing a localized form of minimax complexity for individual functions. Our main result gives function-specific lower and upper bounds on the number of stochastic subgradient evaluations needed to optimize either the function or its "hardest local alternative" to a given numerical precision. The bounds are expressed in terms of a localized and computational analogue of the modulus of continuity that is central to statistical minimax analysis. We show how the computational modulus of continuity can be explicitly calculated in concrete cases, and relates to the curvature of the function at the optimum. We also prove a superefficiency result that demonstrates it is a meaningful benchmark, acting as a computational analogue of the Fisher information in statistical estimation. The nature and practical implications of the results are demonstrated in simulations.

Based on joint work with Sabyasachi Chatterjee, John Lafferty, and Yuancheng Zhu.

## Sedi Bartz

UBC Okanagan

## Zaid Harchoui

Department of Statistics, University of Washington

## Yin Tat Lee

Department of Computer Science, University of Washington

## Zhausong Lu

Department of Mathematics, Simon Fraser University

### Randomized block proximal damped Newton method for composite self-concordant minimization

We consider the composite self-concordant (CSC) minimization problem, which minimizes the sum of a self-concordant function $f$ and a (possibly nonsmooth) proper closed convex function $g$. The CSC minimization is the cornerstone of the path-following interior point methods for solving a broad class of convex optimization problems. It has also found numerous applications in machine learning. The proximal damped Newton (PDN) methods have been well studied in the literature for solving this problem and they enjoy a nice iteration complexity. Given that at each iteration these methods typically require evaluating or accessing the Hessian of $f$ and also need to solve a proximal Newton subproblem, the cost per iteration can be prohibitively high for solving large-scale problems. To alleviate this difficulty, we propose a randomized block proximal damped Newton (RBPDN) method for solving the CSC minimization. Compared to the PDN methods, the computational cost per iteration of RBPDN is usually significantly lower. The computational experiment on a class of regularized logistic regression problems demonstrate that RBPDN is indeed promising in solving large-scale CSC minimization problems. The convergence of RBPDN is also analyzed. As a consequence, the complexity of the full damped Newton methods are improved.


## Terry Rockafellar

Department of Mathematics, University of Washington