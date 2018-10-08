# Lab3

2. Short overflows at n=256
3. Long overflows at n=65536
4. Float overflows at n=34
5. Dobule overflows at n=171
6. Float stops at 15.4037, as it cannot handle the precision of larger values of n.  Double continues growing until the integer is overflowed.
7. The numeric error occurs because the truncation error of the float type causes the value to be slightly less than 4.4.
8. The double is more precise, so the value is read as 4.4 and the for loo
