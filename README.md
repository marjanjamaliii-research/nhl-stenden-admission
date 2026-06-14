# cvds-admission-assignments
NHL Stenden Admission – Debugging Assignments

This repository contains solutions to debugging exercises as part of the NHL Stenden admission process.

Contents

The notebook includes multiple exercises, each structured with:

- A Markdown explanation
- A corresponding code 

Exercise Overview

- Exercise 1 – Set Indexing
  - Problem:
Sets are unordered, so indexing leads to unpredictable results.
  - Solution:
Converted the set to a list before indexing.
- Exercise 2 – Array Swapping
  - Problem:
Values were overwritten during assignment.
  - Solution:
Used a copy of the array before swapping.
- Exercise 3 – Plot Bug
  - Problem:
Precision and recall axes were swapped.
  - Solution:
Corrected axis order.
- Exercise 4 – GAN Debugging
  - Problem   (Structural)
The code assumed a fixed batch size, causing mismatch errors when the last batch was smaller.
  - Solution :
Used dynamic batch sizes
  - Problem   (Cosmetic)
Minor issues in output formatting.
  - Solution :
Improved output formatting

Technologies

- Python
- PyTorch
- NumPy
- Matplotlib



How to Run

1. Open the notebook:
   
   debugging_assignments.ipynb

2. Run all cells:
   
   Kernel → Restart & Run All

3. Ensure required libraries are installed:
   
   pip install torch torchvision matplotlib numpy

