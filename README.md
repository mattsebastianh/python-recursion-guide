# Python Recursion Guide

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A hands-on Jupyter notebook that teaches recursive programming in Python through clear explanations, side‑by‑side iterative comparisons, simple performance checks, and practice exercises.

## What’s inside
- `practical_recursion.ipynb` — a guided notebook covering fundamentals, patterns, performance, and 10 practical case studies.

### Case studies covered
| Case | Topic | Difficulty | Key Concept |
|------|------|------------|-------------|
| 1 | Factorial | Easy | Linear recursion basics |
| 2 | Fibonacci | Medium | Binary recursion, exponential growth |
| 3 | Sum of List | Easy | Processing sequential data |
| 4 | Power Function | Easy | Mathematical recursion |
| 5 | Reverse String | Easy | String manipulation |
| 6 | Countdown | Easy | Visual recursion flow |
| 7 | Palindrome Checker | Medium | Two‑pointer recursion |
| 8 | GCD (Euclidean Algorithm) | Medium | Classical algorithm |
| 9 | Binary Search | Medium | Divide & conquer |
| 10 | Nested List Sum | Hard | Deep recursion with nested structures |

## Requirements
- Python 3.8 or newer
- Jupyter (Notebook or JupyterLab)
- Optional: VS Code with the Python and Jupyter extensions

## Quick start (macOS, zsh)
1) Create and activate a virtual environment (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyter
```

2) Launch Jupyter in this folder and open the notebook:

```bash
jupyter notebook  # or: jupyter lab
```

3) In the UI, open `practical_recursion.ipynb`, then run cells top‑to‑bottom.

### Open in VS Code (optional)
1) Install the "Python" and "Jupyter" extensions.
2) Open the folder, then open `practical_recursion.ipynb`.
3) Select the `.venv` interpreter if prompted and click "Run All".

## Tips while learning recursion
- Start by writing a correct base case; then add the recursive case.
- Use small inputs to trace the call stack and verify the flow.
- Compare recursive vs iterative implementations to understand trade‑offs.
- Python’s default recursion depth is ~1000; deep recursion may raise `RecursionError`. Prefer iterative or optimized approaches, or redesign to avoid deep stacks.

## Troubleshooting
- "command not found: jupyter":
	- Ensure the venv is active and run `pip install jupyter`.
	- If using JupyterLab, install with `pip install jupyterlab` and launch `jupyter lab`.
- VS Code can’t find kernel/interpreter:
	- Select the `.venv` interpreter from the top‑right kernel picker in the notebook.
- RecursionError:
	- Reduce input size, switch to an iterative approach, or apply memoization/alternative patterns.

## License
This project is released under the [MIT License](LICENSE).