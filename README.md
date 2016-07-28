#SimulteDFA
![alt text](https://github.com/Subarno/SimulateDFA/blob/master/img/Screenshot%20from%202016-07-29%2000-28-36.png "OverDracht")
SimulateDFA is an implementation of a datastructure in C that would simulate any Definite Finite Automaton with any number of states and two inputs 0 and 1 for each states respectively.

Inputs necessary to be given are the number of states and the transition state for each input of those states. 

After the DFA is finally built string checking operations can be performed in those DFAs and the visited states might also be matched to prove the validation of the DFA. Confirmation of large string along its visiting states can be tracked by this process very easily.

Requirements: 
--------------
  gcc version 5.2.1 or above
  
Easy Compilation and Run:
-------------------------
  Once you have setup the dependencies, download the source and compile:
`````````````````````````
$ git clone https://github.com/Subarno/SimulateDFA.git
$ cd SimulateDFA
$ gcc main.c -o dfa
$ ./dfa
````````````````````````````
> Happy To Code ... Happy To Live :octocat:


