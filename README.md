# PBIL-MATLAB-GUI

This is a demonstration of the PBIL (Population-Based-Incremental-Learning) Algorithm.

PBIL is a genetic metaherustic algorithm that can be used to solve IP (Integer Programming) problems.

## Problem Context

-To solve the terminal assignment problem.

A connection with a terminal and concentrator is associated with a cost. The goal is to minimise the cost by selecting the appropiate connctions. 
The file called "Solutions" contains the cost table. There are 8 concentrators and 12 terminals. Each concentrator may have no more than 3 connections

## Algorithm

Steps:\
1. Create an epoch of sample solutions.\
2. Work out the cost of each solution.\
3. Find the sample solution with the lowest cost and meeting constraints.\
4. Update the probability vector according to the specified learning rate.\
5. Repeat the process up till a certain number of epochs.
