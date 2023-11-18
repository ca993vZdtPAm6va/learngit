# learngit
This package contains all source codes for 
- Selection Sort

The detail could be found in our [technical report](./Test1_Sorting_Algorithm.pdf).

## Usage Step
1. Compilation. 
```
gcc sort.c -o sort
```
2. Execution.
```
./sort
```
3. Input Files (Format of those files can be found in Appendix)
   1. By default, we have file "config.txt" for configuration.
   2. "data.txt", which is the dataset used in the sorting algorithm.
4. Output Files (Format of those files can be found in Appendix)
   1. "output.txt", which is the output of the sorting algorithm.
   2. "stat.txt", which captures the number of swapping of the sorting algorithm.
   3. "time.txt", which captures the time statistics of the sorting algorithm.


## Appendix A. Format of Configure File "config.txt"
Each line corresponds to a parameter. <br>
> 1. The file name of input dataset
> 2. Parameter 1
> 3. Parameter 2
> 4. Parameter 3
> 5. Parameter 4

## Appendix B. Format of Input Dataset "data.txt"
A line corresponds to an unordered sequence. Each element in a sequence is separated by a space " ". <br>
The format of the line is <br>
> <elem 1> <elem 2> <elem 3> ... <--- the input sequence <br>


## Appendix C. Format of "output.txt"
A line corresponds to a sequence in ascending order. Each element in a sequence is separated by a space " ". <br>
The format of the line is <br>
> <elem 1> <elem 2> <elem 3> ... <--- the output sequence <br>

## Appendix D. Format of "stat.txt"
A line corresponds to the number of swapping of the sorting algorithm. <br>
The format of the line is <br>
> <no. of swapping> <br>


## Appendix E. Format of "time.txt"
Each line corresponds to a user time and system time. <br>
> 1. time for reading the dataset.
> 2. time for sorting the input sequence.
> 3. time for writing the output file.
> 4. time for the sum of all the parts.

