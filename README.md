# CSYS5040 Criticality in Dynamical Systems Assignment 2

**Due Date**: This is assignment is due in TurnItIn by Sunday, September the 15th. This assignment is worth 25% of your final mark.

You must do all of your working in a Mathematica notebook that I can run (no pdfs of Mathematica notebooks).

The * for some questions indicate the relative difficulty of the question. This is an individual assessment; your answers must reflect your own work. Marks will be based on the correctness of each answer, the effort put into exploring each question, and the originality of the examples you choose to look at. You are strongly encouraged to read beyond the class material to get a higher grade.

## Question 1 (7.5%)
### The dynamics of a stochastic differential equation
#### a.
Choose the constant valued parameters (i.e., $\mu$, $\sigma$, and $x_0$) of a linear stochastic differential equation of the form: $dx = \mu dt + \sigma dW_t$ where $\sigma$ is the strength of the stochastic (noise) term, $x_0$ is the initial starting point. Plot the time series of the solution, making sure $\sigma$ is not equal to zero (it can be positive or negative though). Choose some numerical value (for ‘boundary’) that has the same sign as $\mu$, run some simulations of your solution. Determine if your solution ever crosses the boundary and if so, at what value of $t$ does your solution cross it? Without simulating your solution, discuss how you can know when to expect the solution to cross the boundary.

#### b. *
Repeat part a. except that the stochastic differential equation is now non-linear, e.g., $dx = (\mu + x^n) dt + \sigma dW_t$ or uses even higher order terms in $x$, e.g., $dx = (\mu + x^n + x^m) dt + \sigma dW_t$. The more sophisticated your model is, the higher your score will be for this part and consequently for part 1 c. below. Do not implement the same equations here that are needed for Question 2.a.

#### c.
Write a single paragraph on one application of the methods you used in parts a. and b. For example, you can look up: “drift diffusion” and “neural network”, “two alternative forced choice task” (e.g. here: https://tinyurl.com/yygku3oa ), “Ornstein-Uhlenbeck process”, or see here: https://en.wikipedia.org/wiki/Ornstein–Uhlenbeck_process.

## Question 2 (7.5%)
### Plotting non-linear functions for a non-linear map
#### a.
From the article we looked at in Week 4, implement one of the non-linear stochastic neural models. Do not implement the same equations you used for 1.b. For this first step, all you have to do is replicate the work shown in class but using either 1 or 2 stochastic non-linear equations that you will find in the articles listed below where a decision is reached once a “decision variable” crosses a boundary threshold.
For the different equations for each system see pages 705 to 707 of the article here: https://sites.engineering.ucsb.edu/~moehlis/moehlis_papers/psych.pdf. Or look at the different equations listed on the Wikipedia page under “Other Models” here: https://en.wikipedia.org/wiki/Two-alternative_forced_choice.

#### b. *
Find an article (using Google Scholar etc.) that has used the model you implemented in part 2a. and illustrate some aspect of the results from that article using the model you’ve just implemented.

#### c.
Discuss the impact of the model you’ve used in the context of the article you’ve found. For example, discuss why this stochastic model was used rather than some other model, or what the parameters mean in a practical setting, or what new interpretation the model has provided in the area of study etc.

## Question 3 (10%)
### Parameters in non-linear dynamical systems
**Based on your answer to Question 1 for the non-linear system, write a Mathematica function that shows what happens when a parameter value, e.g., $\mu$ or $\sigma$ changes and the system switches from one equilibrium state to another. See the Mathematica notebook from Week 1, at the end of the notebook there is a stochastic diffusion processes with more than one stationary state. We didn’t discuss this model but I want you to base your answer on the ideas outlined there. Note that the stationary state the system was attracted to (settled in) depended on the initial starting point $x_0$. For this question, using a system with more than one stationary state, I want you to let the system find its stationary state (i.e., it is in equilibrium) and then change the parameter values so that the system switches from one equilibrium point to another by going through a tipping point. The minimum you need to do to pass this question is to plot the time series of the system passing through this tipping point.**

# CSYS5040 Assignment 2

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
