# Automata-Theory
My personal notes on Automata

## Theory of Computation
* Abstract

### Applications
* Compiler design
* computer architecture
* string search (Finite state machine)

Example
1. Program to compute whether a binary string ends in 0 - easy
2. Program to check if the binary file is written with legal java syntax - tough but still possible
3. Program to check if the java program is free of any possible infinite loop. - can't be solved.

what we are studying is to know what we can compute and what is not possible

### Finite state machines
moving from inner most layer to out
1. Finite state machine
2. context free language
3. Turing machines
4. Undecidable

There are many levels of complexity in between these layers as well.

-----
Strings with even number of zeros
You need to ask yourself can I do this with a finite amount of memory?

you can think of this problem having 2 states, one with even number of zeros and another with odd number of zeros

transition function
if you see a zero then switch to the other state, if its 1 stay

notation double circle to identify a finish state.
-----
even number of zero and even number of one.

we can think of this problem in 4 states, ee (both even number and expectation), eo (even zero and odd ones), oe and oo respectively.


there can be more than 1 finite state machine for a problem. and you can wonder given a problem, can there be a minimum finite state machine with minimal states
