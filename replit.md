# C Lists and Stacks Lab

## Overview
A C programming lab (university exercise) focused on implementing List (ArrayList) and Stack data structures. Students implement functions in `exercises.c`.

## Project Structure
- `exercises.c` — Student implementation file (the only file students should modify)
- `arraylist.h` / `arraylist.c` — List (ArrayList) TDA implementation
- `stack.h` — Stack TDA interface
- `test.c` — Test suite
- `test.sh` — Build and test runner script
- `log` — Test run log file

## Running Tests
Open the Shell and run:
```bash
bash test.sh
```

This will:
1. Compile `test.c` with gcc
2. Run the compiled binary and show test results
3. Optionally push progress to GitHub

## Workflow
- **Run Tests**: Configured as a console workflow (`bash test.sh`), not auto-started since it's interactive.

## Language & Build
- Language: C (GCC 14.3.0)
- No frontend, no backend server — pure C compilation
- No package manager needed
