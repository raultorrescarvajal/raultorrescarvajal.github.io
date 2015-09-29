---
published: false
title: Baseline algorithm
layout: post
---
I liked the work presented on the paper "A Tree Kernel Based Approach for Clone Detection". There, the authors proposed an algorithm to compare Abstract Syntax Trees (ASTs) using a tree kernel that takes into account four features for each node. Such characterization permits to modulate the weight given  to a syntactical unit according to the impact it has inside the code. Hence, I selected their algorithm as the baseline for my study, in which I use a string kernel applied over ASTs and the Linear Representation of LLVM. I will report my progress and findings in this blog.

<a href="jjj">jjj</a>