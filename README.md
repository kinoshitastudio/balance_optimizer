# balance_optimizer

```text
      ____    _    _        _    _   _  ____ _____ 
     | __ )  / \  | |      / \  | \ | |/ ___| ____|
     |  _ \ / _ \ | |     / _ \ |  \| | |   |  _|  
     | |_) / ___ \| |___ / ___ \| |\  | |___| |___ 
     |____/_/   \_\_____/_/   \_\_| \_|\____|_____|

     [ A ] <---------( EQUILIBRIUM )---------> [ B ]
     
     Minimalism is not a lack of something.
     It's simply the perfect amount of something.
     Abstract (English)

     
balance_optimizer is an experimental prototype designed to mathematically validate "Subtractive Design" in UX through algorithmic optimization.

As a designer, deciding what to remove requires intuition. This tool bridges that intuition with logic. Inspired by Counterfactual Regret Minimization (CFR), it utilizes Thompson Sampling to discover the perfect equilibrium point where a design is most effective yet most minimal.

Core Concept: Subtractive Design
The fear of removing elements often stems from the uncertainty of losing essential information. balance_optimizer transforms this uncertainty into data-driven confidence.

Exploration: Testing a more minimal variant (Variant B) to uncover potential improvements in user focus.

Exploitation: Automatically increasing the exposure of the higher-performing variant to minimize "regret" (lost opportunity).

Features
Real-time Optimization: Dynamic traffic allocation via a Multi-Armed Bandit algorithm.

Visualized Probability: Real-time tracking of Posterior Distributions to intuitively grasp statistical confidence.

Minimalist Interface: A high-contrast, monochrome UI designed to eliminate cognitive noise.

Tech Stack
Framework: Vanilla JS / HTML / CSS

Algorithm: Thompson Sampling (Beta Distribution)

Design Philosophy: Subtractive Design / Grid System

Usage
Define Variant A (the baseline) and Variant B (the subtracted version).

As virtual or real impressions occur, the algorithm selects the optimal variant to display.

Over time, the system converges on the design that achieves the best balance of silence and performance.

Link
Live Demo

© 2026 Kinoshita Studio / 99letters. All rights reserved.
Design by subtraction. Driven by logic.