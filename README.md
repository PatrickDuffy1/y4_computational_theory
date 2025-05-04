# Year 4 Computational Theory

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PatrickDuffy1/y4_computational_theory.git
   ```

2. Install Jupyter Lab (if not already installed) by running the following command in your terminal:
   ```bash
   pip install jupyterlab
   ```

3. Navigate to the cloned repository in your terminal:
   ```bash
   cd y4_computational_theory
   ```

4. Start Jupyter Lab:
   ```bash
   jupyter lab
   ```

5. Open the tasks.ipynb notebook and run the program.

## Description

This project contains 8 tasks, mostly related to [FIPS 180-4: Secure Hash Standard (SHS)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf). The tasks include bitwise operations, hashing algorithms, prime number theory, and theoretical computation models like Turing Machines.

### Tasks Overview

- **Task 1: Binary Representations**  
  Implemented bitwise operations in Python, including left/right bit rotation, bitwise choice (`ch`) and majority (`maj`) functions, all components in SHA algorithms.

- **Task 2: Hash Functions**  
  Translated a C hash function from The C Programming Language by Brian Kernighan and Dennis Ritchie into Python, tested its behavior, and analysed the reason that constants like `31` and `101` were used in the hash computation.

- **Task 3: SHA256**  
  Created a function to compute and display the SHA256 padding for the contents of a file, based on the format specified in [FIPS 180-4: Secure Hash Standard (SHS)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf).

- **Task 4: Prime Numbers**  
  Computed the first 100 prime numbers using two different well-known algorithms (Trial Division and Wilson’s Theorem).

- **Task 5: Roots**  
  Extracted the first 32 bits of the fractional parts of the square roots of the first 100 prime numbers.

- **Task 6: Proof of Work**  
  Used a list of English words to identify words whose SHA256 hashes have the highest number of leading zero bits, simulating a simplified proof-of-work system.

- **Task 7: Turing Machines**  
  Designed a Turing Machine that adds one to a binary number.

- **Task 8: Computational Complexity**  
  Implemented bubble sort in Python and counted the comparisons.
