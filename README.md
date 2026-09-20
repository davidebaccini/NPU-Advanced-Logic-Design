# Introduction
Neural Processing Unit created for the Advanced Logica Design Exam Project

# Architecture
The NPU will be divided into Control Unit (CU) and Datapath.
The CU will be the ARM CPU built-in in the FPGA board while the Datapath will be designed by us.

## Control Unit
The ARM CPU executes a C program to control all the aspects of the NPU,

## Datapath
We will be using Multiplier Accumulator (MACs) blocks on the FPGA (ZedBoard Zinq 7000) to perform the neuron calculations.

### First Test
The first test consists of instantiating a single neuron and checking wether the NPU is working properly.

### Second Test
Done the first step the NPU will be scaled to 16 hardware neurons.

### Potential Final Step
The final step that may be achieved is to code this in order to be extremely flexible. Given a set of constants like number of neurons and weight, bias size the FPGA fabric should adapt and simulate the new network.

# Goal
<<<<<<< HEAD
The goal is to obtain a fully working NPU that can "run" a small neural network capable of predicting a letter given a word or a sentence.
=======
The goal is to obtain a fully working NPU that can "run" a small neural network capable of predicting a letter given a word or a sentence.
>>>>>>> 9c38b9af77c53ec586e59ae8c66556fe3c25cfa2
