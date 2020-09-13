# Finite-Automata-Simulator

DFA and NFA to DFA converter:

Theory of machines and languages course project. 
`Finaite Automata Simulator- Acceptance of DFA.py` reads a DFA from `DFA.txt` in the following input order and then gets a string from input. Then it outputs whether input string was accepted by DFA or not. 
`Finaite Automata Simulator- NFA to DFA.py` reads a NFA from `NFA.txt` in the following input order and then writes equivalent DFA to `DFA.txt`.

Input file format:


* First line are automata's alphabet separated by space. 
* Second line are states in the automata separated by space. 
* Third line is initial state of automata. 
* Fourth line are final states separated by space. 
* And the rest are transitions in states in the automata and each line specifies one transition in the automata (that has the following order): 

<current state> <letter> <next state>
  
Sample input file:

0 1
q0 q1 q2
q0
q1
q0 λ q1
q0 0 q1
q1 0 q0
q1 1 q1
q1 0 q2
q1 1 q2
q2 0 q2
q2 1 q1
