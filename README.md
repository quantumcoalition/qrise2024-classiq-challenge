# Classiq QRISE 2024 Challenge
Simulating Coupled Classical Oscillators in Practice

## Background
The progress of quantum computers in the last few years has been immense, with better and better quantum computers being developed each year. Nowadays there are quantum computers with hundreds of qubits that can compute quantum algorithms with circuit depth of up to a few thousand and still receive a significant signal. One of the key challenges is the development of efficient and novel quantum algorithms that are useful and offer exponential advantage over classical methods. One of the very few algorithms we know of under this definition is the [Exponential Quantum Speedup in Simulating Coupled Classical Oscillators](https://journals.aps.org/prx/pdf/10.1103/PhysRevX.13.041041) work, presented in 2023 by Ryan Babbush et al.

Like most quantum algorithms papers, this is a theoretical work. Taking a theoretical paper and implementing it in practice is a massive challenge with many obstacles that need to be overcome, both practical and theoretical.

## Challenge Statement
**Your challenge is to implement the above paper using the Classiq platform.** Classiq is an end-to-end quantum software platform that enables you to design, optimize, analyze and execute quantum algorithms. Classiq utilizes the power of high-level functional design and enables you to focus on the algorithm you want to create rather than on the quantum circuit implementation of it.

The goal is to implement the largest and most advanced implementation of the above algorithm. You should aim to compile a circuit on 70-150 qubits with a depth between 10K-30K. In order to achieve the end result, it is highly recommended to work step-by-step, and to start with the smallest relevant example of the algorithm. Build your algorithm in a parametric way, utilizing high-level functional design, such that it will be easy for you to scale from a small, degenerate example (that can be simulated) to a large example.

## Getting started
1. Understand the basics of [the paper](https://journals.aps.org/prx/pdf/10.1103/PhysRevX.13.041041)
    1.   Watch the following videos where the authors explain the work: [video1](https://www.youtube.com/watch?v=d6LU9DYuErs), [video2](https://www.youtube.com/watch?v=lzw9H1fNW6U), [video3](https://www.youtube.com/watch?v=rY_8H78oDlQ)
2. Learn the [Classiq platform](https://platform.classiq.io/)
   1. Complete the Classiq workshop notebooks
4.   Iteratively start implementing the smallest viable example of the algorithm while understanding the paper in-depth and mastering the Classiq algorithm
5.   Increase the complexity of the example and find the most advanced instance of the algorithm you can simulate.
