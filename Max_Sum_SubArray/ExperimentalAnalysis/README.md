# Max Sum Subarray Analysis
### Comparing 4 algorithms' efficiency in finding the largest sum in a contiguous subarray within a one-dimensional array of numbers.

```MSS_ExpAnalysis.cpp``` contains the code we used to run the algorithms for runtime analysis.  The output is only the average runtime in seconds, separated by newlines.  It is designed to run 10 incrementally increasing arrays, each 10 times, through a single algorithm, and to take the average run time of each same-sized array, which is then output for analysis.

Compile with the including makefile.  Or use this command:
```g++ -o MSS_ExpAnalysis MSS_ExpAnalysis.cpp```

After compilation, MSS_ExpAnalysis is the name of the executable.  It requires four CLI arguments:
1.  ```n_initial```  -  the intial size of array.  This is also the increment size.
2. ```numberOfRuns``` - to be averaged over.  Suggested is 10
3.   ```algFlag``` - this selects the algorithm to be run:
- ```1```: Algorithm 1: Enumeration
- ```2```: Algorithm 2: Better Enumeration
- ```3```: Algorithm 3: Divide and Conquer
- ```4```: Algorithm 4: Linear-time
4. ```tracerFlag``` - this is for tracing/testing.  ```1``` = ON, ```0``` = OFF


Here are our recommended commands to run each of the respective algorithms:
1. ```MSS_ExpAnalysis 100 10 1 0```
2. ```MSS_ExpAnalysis 1000 10 2 0```
3. ```MSS_ExpAnalysis 10000 10 3 0```
4. ```MSS_ExpAnalysis 100000 10 4 0```

Don’t turn on the tracerFlag for larger arrays; it will output every element!
