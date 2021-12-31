# RNG_tools
A C++ class that implements the ran2 random number generator, along 
with some useful helper functions:

  - random number between 0 and 1
  - random integer in a given range
  - Normally distributed numbers using the Box-Mueller algorithm
  - RNG state that can be saved to (read from) a file

In addition, the user can read in a PDF from a file.  This PDF is 
taken to be continuous piecewise linear, and so its CDF is C1 
continuous piecewise quadratic.
