# Linker-Java

This program is written in Java with the main method in Two_Pass.java. To compile the script,
execute Two_Pass.java.
This script mimics the function of a two_pass linker, the first pass goes through the modules,
calculates the base address for each module and then goes through a list that stores all the
usages in order to determine the absolute address for external addresses. Pass two utilizes the
base address to generate the actual outputs.
