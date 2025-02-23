# Unclosed File Handle Bug in Python

This repository demonstrates a common yet easily overlooked bug in Python: failing to close a file handle after it is no longer needed.  Unclosed file handles can lead to resource leaks and potentially hinder application performance or stability, especially when dealing with a large number of files.

The `bug.py` file contains the buggy code, while `bugSolution.py` shows the corrected version with proper file handling.

## How to Reproduce

1. Clone this repository.
2. Run `bug.py`.  Note that even if no errors are explicitly reported, the file might remain open.
3. Run `bugSolution.py` to see the improved, resource-safe version.