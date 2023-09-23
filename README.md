# Fermats_Factorization

This C++ code is based on the fact that every odd number can be represented as a difference of squares of two numbers. 

Fermat's Factorization algorithm: 
Input: a positive odd number n 
Output: a factor of n, or message stating that n is a prime. 
**Step 1:** Begin with x = $\lfloor \sqrt{n}\rfloor$. If n = $x^{2}$, then x is a factor of n, and the code stops; otherwise, increase x by one and go to step 2.

**Step 2:** If x = $\dfrac{\left( n+1\right) }{2}$, then n is prime and the code stops; otherwise compute y = $\sqrt{x^{2}-n}$

**Step 3:** If y is an integer, then n has factors x+y and x-y, and the code stops; otherwise, increase x by one and return to step 2.
