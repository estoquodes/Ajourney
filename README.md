# Context switch

## 1

P2 blocks awaiting data from P1
P1 marks the starting time.
P1 sends token to P2.
P1 attempts to read a response token from P2. This induces a context switch.
P2 is scheduled and receives the token.
P2 sends a response token to P1.
P2 attempts read a response token from P1. This induces a context switch.
P1 is scheduled and receives the token.
P1 marks the end time.

https://www.geeksforgeeks.org/measure-time-spent-context-switch/

# Perf

Perf is a profiler tool for Linux based system that abstracts away CPU hardware differences in Linux performance measurements and presents a simple commandline interface.

## Installation

Use command line in Linux system.

```bash

(the command)
```

## Usage

```python
import (library)
```

## Contributing

Startup tool for the research travel.

## License
[MIT](https://choosealicense.com/licenses/mit/)



