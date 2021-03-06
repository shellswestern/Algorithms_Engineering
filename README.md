# Algorithms_Engineering
Algorithms implementation in C++ to:

* Compute Fibonacci Number derived from the definition, using linear memory, and using constant memory 
* Compute the maximum number of floating-point operations (FLOPS) per second on a machine in single-threaded mode
* Solve Longest Common Subsequence (LCS) problem 
* Compute the memory bandwidth using OpenMP
* Unit testing in three situations

(More specific information for each algorithm can be found in the .pdf file in the same folder)

## Usage
1. Clone the repository
```markdown
  git clone https://github.com/shellswestern/Algorithms_Engineering.git
```
2. Run a program 
E.g. for Fibonacci Number program:
```markdown
  mkdir build
  cd build
  cmake ..
  cmake --build .
  ./fib 6 (an example number)
```
Run the unit tests:
```markdown
  ctest -V
```
