# Coin Change Algorithm Comparison
### *DO NOT RUN IN MODE 1 WITH ANY A GREATER THAN 19*, *It's too big of an Big-O"

 
 ### To compile:
1. Navigate to the directory containing the .hpp, .cpp, and makefile files
2. Enter command “make” or “make coinChange”

## To run:
1. Edit main.cpp constants to suit purpose

- MODE 0 : analysis mode, main will print 10 running times in seconds, the average in milliseconds, and the minCoins results from each algorithm, for each V in the input file and A specified by TESTING.
   - TESTING 0: wildcard for testing varying amounts. Will not run the naive brute force implementation. (currently set to test input denominations with A = 1 - A = 200)
   - TESTING 1: tests all algorithms with A=1 - A = 18  (naiveChange cannot handle higher A values)
   - TESTING 2: tests greedy and DP algorithms with A =  2000 - A = 2200

- MODE 1 : normal mode, main will print out the coin denominations (V[ ]), quantities of each coin denomination, the minimum number of coins required to make change of A (sum of the number of coins required), and finally, A (the amount we’re making change for) from each algorithm for each A and V[] in the input file.
   - Note: MODE should already be set to 1

- MODE 2 : debug. Same as Mode 1 but with a few added trace statements

2. From the directory containing the executable, enter:
		```coinChange <inputFileName.extension>```


### To remove:
enter ```make clean``` from within the directory containing the executable.

