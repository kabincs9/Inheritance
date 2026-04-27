# 🧬 Inheritance - Blood Type Simulator

![C](https://img.shields.io/badge/Language-C-blue.svg)
![CS50](https://img.shields.io/badge/CS50-Week%205-orange.svg)
![Genetics](https://img.shields.io/badge/Genetics-Blood%20Type-green.svg)

A beautiful C program that simulates **genetic inheritance** of blood types across multiple generations of a family tree.

## ✨ Overview

This program creates a family tree of any number of generations and realistically models how blood types (A, B, AB, O) are passed from parents to children based on actual genetics.

Each person has two alleles, and the child randomly inherits one allele from each parent.

## 🎯 Features

- ✅ Builds a recursive family tree using structs
- ✅ Supports any number of generations
- ✅ Accurately simulates blood type inheritance:
  - A, B, AB, and O blood types
  - Correct allele combinations (AA, AO, BB, BO, AB, OO)
- ✅ Uses dynamic memory allocation (`malloc`)
- ✅ Properly frees all allocated memory to prevent leaks
- ✅ Clean and interactive terminal output
- ✅ Random but biologically valid inheritance

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/kabincs9/inheritance.git
cd inheritance

# Compile
make

# Run the program
./inheritance generations
