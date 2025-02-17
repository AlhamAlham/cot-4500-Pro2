# cot-4500-Pro2 - Approximation Methods

## Overview
This project implements 4 algorithms in Python:
1. **Nevilles Method**
2. **Newton's Forward Method**
3. **Hermite Polynomial Approximation**
4. **Cubic-Spline Interpolation**

Each algorithm follows the specifications given in Chapter 3 of the course material.

## Repository Structure
cot-4500-Pro2/
\│-- src/ \
│ │-- main/ \
│ │ │-- init.py \
│ │ │-- assignment_2.py \
│ │-- test/ \
│ │ │-- init.py \
│ │ │-- test_assignment_2.py \
│-- requirements.txt \
│-- README.md\


## Installation & Setup
### **1. Clone the Repository**
```bash
git clone https://github.com/AlhamAlham/cot-4500-Pro2
cd cot-4500-Pro2
```
### **2. Install Dependencies**
This project requires Python and the necessary dependencies, which are listed in the requirements.txt file. Install them using pip:
```bash
pip install -r requirements.txt
```
### **3. Run the Code**
Once the dependencies are installed, you can run the main script:
```bash
python src/main/assignment_2.py
```
### **4. Running Tests**
To run the unit tests (which are not the same as the assignment, these are a random set of tests I created), use the following command:
```bash
python -m unittest discover src/test
```
### **Usage**
The approxiation/matrix algorithms can be used by calling the corresponding functions in assignment_2.py.
Example usage and further details on the implementation can be found in the code comments.

