# Makefile for CS 2150 post-lab 11
# Hanzhang zhao hz9xs

# Defines the C++ compiler we'll be using
CXX = clang++

# Defines the flags we'll be passing to the C++ compiler
CXXFLAGS = -Wall -g -std=c++11 -O2

# All of the .o files for our program
OBJECTS = solvePuzzle.o puzzle.o

# Compile our files into a.out
a.out: $(OBJECTS)
	$(CXX) $(CXXFLAGS) $(OBJECTS)
	doxygen
	

# This will clean up (remove) all our object files.  The -f option
# tells rm to forcily remove the files (i.e. don't ask if they should
# be removed or not).  This removes object files (*.o) and Emacs
# backup files (*~)
clean:
	-rm -f *.o *~
