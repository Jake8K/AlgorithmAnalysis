# Traveling Salesman Problem
### Different algorithmic approaches to approximating a solution to this NP-Hard problem

### to compile:
- ```make```
- ```g++ -std=c++11 main.cpp -o tsp```

## to run:
```tsp <input_file> -u```
- Program will run TSP algorithm on inputfile.txt and give the best possible solution, without any time constraint (-u == unlimited time).
```tsp <input_file> <int>```
- Program will run TSP algorithm and report the best solution it can find for inputfile.txt within the constraint of the time limit imposed (in minutes, represented as whole numbers)

In either case, the algorithm results will be printed to inputfile.ext.tour, within the original file’s directory.
- The first line of the file is the best path length.
- Subsequent lines represent the city IDs in the order that they should be visited.

- When entering the input file, include the extension.
- If the file is in a separate directory, include the path as part of the name: ../path/to/input/file.ext

### to remove executable:
- ```make clean```
