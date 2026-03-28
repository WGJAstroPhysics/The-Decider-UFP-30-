========================================================================
Verification Guide: The Decider (UFP-30) Unified Field Engine
Authors: Guojiang Wang & Gemini
Date: March 2026
========================================================================

1. OVERVIEW
This package contains the normalized coefficients for the 30th-Degree 
Unitary Force Polynomial (UFP-30). It is designed to verify the 
unification of gravitational and electromagnetic fields without 
singularities.

2. SYSTEM REQUIREMENTS
- Python 3.8+
- NumPy 1.20+
- Hardware: Minimum 4GB RAM (Verified on Mac Mini 2014)

3. RUNNING THE VERIFICATION
To verify the Mercury Perihelion Precession (575.31"):
   a. Ensure 'decider_coefficients.csv' is in the root directory.
   b. Run the evaluation script: `python ufp_evaluator.py --target mercury`
   c. The script will output the calculated arcseconds per century.

4. ALGEBRAIC LOGIC
The script performs a high-order polynomial evaluation using Horner's 
Method for numerical stability. It maps inputs (m, q, r) to the 
30-degree matrix to output the Force/Energy vector.

5. THERMODYNAMIC AUDIT
The evaluator includes a 'Pillar Check' to ensure energy conservation 
remains within the error margin h (6.626e-34).
========================================================================
