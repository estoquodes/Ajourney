# 1. Context switch

## a) Procedure

1. P2 blocks awaiting data from P1.
2. P1 marks the starting time.
3. P1 sends token to P2.
4. P1 attempts to read a response token from P2. This induces a context switch.
5. P2 is scheduled and receives the token.
6. P2 sends a response token to P1.
7. P2 attempts read a response token from P1. This induces a context switch.
8. P1 is scheduled and receives the token.
9. P1 marks the end time.

https://www.geeksforgeeks.org/measure-time-spent-context-switch/

# 2. Last Level Cache (LLC)

## a) General intro

https://dl.acm.org/doi/10.1145/3302424.3303977

# 3. Read performance on mac OS X

## a) Using Time Profiler in Instruments

https://developer.apple.com/videos/play/wwdc2016/418/

# 4. How Does CPU Cache Work and What Are L1, L2, and L3?

## a)

https://www.makeuseof.com/tag/what-is-cpu-cache/

# Problems met

## a) on EC2 instance

## b) Virtual environment on Windows 10

https://github.com/microsoft/perfview/issues/974

# Perf

Perf is a profiler tool for Linux based system that abstracts away CPU hardware differences in Linux performance measurements and presents a simple commandline interface.

## License
[MIT](https://choosealicense.com/licenses/mit/)



