# Active Intent Demonstration in Games

Imagine we drive on highway and we do not have the phone number of nearby drivers, how should we demonstrate our intent (urgently driving to a ceremony or casually driving for vacation) to some drivers who are attempting to merge onto your lane? 

Our algorithm leverages iLQGames and iLQR to plan in the joint physical and belief space such that you can strategically demonstrate your intent to other drivers. 

If you want to learn more, please check out our paper: [Intent Demonstration in General-Sum Dynamic Games via Iterative Linear-Quadratic Approximations](https://arxiv.org/pdf/2402.10182).

# Installation guide:

We use Julia 1.6.7

1. cd to the folder `examples/final_experiments`
2. For running the nonlinear highway driving experiments: we run the following code in terminal: julia --project highway.jl
3. For running the nonlinear hri experiments: we run the following code in terminal: julia --project hri.jl


The experiment codes for the highway platooning and the human-robot furniture moving examples can be found in `examples/final_experiments/`. We will release the code for multi-robot manipulation and shared controlled lunar lander soon. They are LQ games with linear estimation dynamics and solved by matlab. 

If you have any question, feel free to reach out the authors. Thank you!
