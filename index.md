---
layout: default
title: Home
nav_order: 1
description: "L3 Programming Language"
permalink: /
---

# L3 Programming Language

L3 is designed to maximize developer **productivity** and runtime **performance**.

# Features (WIP)

## Simple

- [ ] 0 dependency management - no need to download, build, or include or use a package manager.
- [x] 1 integer type.
- [ ] 1 floating point type.
- [x] 2 container types.
- [x] GUI editor - don't waste time on formatting & style, better code nagivation, and more.
- [x] Arguments always passed by reference (zero overhead).

## Safe

- [ ] Zero overhead automatic memory management.
- [ ] Zero overhead automatic bound checking.
- [ ] No multithreading bugs.

## Fast

- [ ] Automatic memory layout optimiztaions.
- [ ] Automatic vectorization.
- [ ] Automatic parallelism.
- [ ] Automatic heterogeneous computing.
- [ ] Automatic distributed computing.

And many more automatic high level optimizations.

# Benchmarks

The benchmarks measure the performance of code with similar level of complexity.  
The reason is that performance is 2 dimentional problem - running time and the amount of programming work.  
Given full control over the hardware, infinite time, and sufficiently smart programmer, an optimal implementation can be achieved, but it's not feasible.

In other words the purpose of these benchmarks is to measure how much speedup you get for the same amount of programming work.

## Find smallest

Insert 10 random [0,100] integers into a container, and then find the smallest one.
<object data="/assets/plots/find_smallest.svg" type="image/svg+xml"></object>

## Lookup

Insert 100 random {[0,99],[0,99]} key-value pairs of integers into a map, and then randomly lookup one of these elements.
<object data="/assets/plots/lookup.svg" type="image/svg+xml"></object>

## Benchmarking machine:
- **CPU:** i7-6700K @ 4.00 GHz
- **RAM:** 2x4GB DDR3 @ 1333 MHz
- **Operating System:** Windows 10
- **Compiler:** Visual Studio 16.7.4