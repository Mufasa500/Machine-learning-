# Machine-learning-
Project Readme

This project contains two problems: banlet and treemap.

Banlet Problem

banlet_main
The banlet_main program takes an input string from stdin and writes out a graphic representation of the string in a larger font to stdout. The graphics is generated using ASCII characters.

banlet_demo
The banlet_demo program demonstrates the use of banlet library by printing the string "Hello, world!".

test_banlet_funcs1
The test_banlet_funcs1 program tests the correctness of banlet library functions banlet_puts and banlet_putc.

test_banlet_funcs2
The test_banlet_funcs2 program tests the correctness of banlet library functions banlet_wputs, banlet_wputc, and banlet_wprintf.

Treemap Problem

treemap_main
The treemap_main program takes an input file and prints out a tree map of the file to stdout. The tree map displays the relative sizes of directories and files in the file system.

test_treemap_verify
The test_treemap_verify program tests the correctness of treemap library functions verify_treemap and get_treemap.

Makefile

The Makefile provides the following targets:

all: build all programs
clean: remove all compiled items
help: print the usage instructions
zip: create a zip file for submission
prob1: build targets associated with problem 1
prob2: build targets associated with problem 2
prob3: build targets associated with problem 3
test: run all tests
test-prob1: run tests for problem 1
test-prob2: run tests for problem 2
test-prob3: run tests for problem 3
To run a specific test, set the testnum variable, for example, make test-prob2 testnum=5 runs problem 2 test #5 only.

