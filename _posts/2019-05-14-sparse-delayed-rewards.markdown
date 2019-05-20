---
layout: post
title: "My First Post"
date: "2019-05-14 20:17:13 -0500"
---

- would be cool to have expandable tabs so when clicked on branch it expanded to sub branches and individual solutions
- delayed and sparse are two separate problems: delayed is fundamental to reinforcement learning. Sparse is fundamental to machine learning in general
- Major contributions:
  1. **Definition of integral problem to RL for rookies and experts**
  2. **Delayed and Sparse rewards are different**
  3. DOE for delayed vs sparse rewards
  4. **Organization of solutions for sparse and delayed Rewards**
  5. DOE for Solutions
  6. How causality relates
  7. How Markov assumption relates
  8. Systematic way to identify if problem is a "sparse" or "delayed" problem
  9. Systematic way to apply solutions or combinations of Solutions


# Abstract
This is an abstract on the items....

# Intro
One of the outstanding research questions within RL is how to learn from reward signals that may be **sparse**, **delayed**, or both. Many applications of Reinforcement Learning contain reward signals that are both **sparse** and **delayed** from the action that caused them.  

**Example**
- Need to come up with example that can scale well and be repeatedly used (is rich)

- Many real-world problems contain [reward functions]() that .
- For example:  Health benefits from exercising.
- The goal is to extract as much predictive power as possible from the reward signal.  
- the challenge within this example is...

**Credit assignment**

**Sparse vs Delayed**
- The research community is confusing sparse and delayed rewards
- Define sparse rewards functionally
- Define delayed rewards functionally

**Example in Depth**
- An example... using extremes to get the point across.
- Visual

# Background
- Define sparse rewards equations
- Define delayed Rewards equations
- visual example

- credit assignment

- example of simulations where x axis is length of delay and y is the median learning across several episodes

- Extract what is really happening...
- So what is happening here?  Boostrapping using one step bellman update is mudding the credit assignment

# Branches

### Problems
- Credit assignment problem?;  This is a more general version of the problem, also slicing RL from a different angle

1. Sparse
  - class imbalance
2. Delayed


### Solutions
##### Delayed Rewards
- every one of the solutions below is implementing temporal abstraction

1. Reward shaping
  - meta learning
  - n step
2. GVF
3. HRL
4. Imagination
5. dfs

##### Sparse rewards
1. HER
2. Prioritized ER

# Module Image for Bigger Picture

# Solution Descriptions

# Moving Forward

1. DOE for delayed vs sparse rewards
2. DOE for Solutions
3. How causality relates
7. How Markov assumption relates
8. Systematic way to identify if problem is a "sparse" or "delayed" problem
9. Systematic way to apply solutions or combinations of Solutions
10. Diversity/complexity
11. Credit assignment
12. stochastic
