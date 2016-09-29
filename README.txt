Question :
- Implement cartesian product in any language of your choice without using for loop, arrays (Brute force).
Input should be read from 2 flat text files.

Solution :
- Read all the lines from input file2 and stored it in ArrayList.
- Read all the lines from input file1 and stored it as key in HashMap, stored above ArrayList as value for all the keys.
- Iterated through HashMap and wrote output to file

Assumption :
- There are no duplicate records in one of the input file.

Below is the performance evaluation of entire program.

500 tuples in each input file :
Total time taken in mili seconds :::: 297

1000 tuples in each input file :
Total time taken in mili seconds :::: 826

3000 tuples in each input file :
Total time taken in mili seconds :::: 4467

5000 tuples in each input file :
Total time taken in mili seconds :::: 9973

7000 tuples in each input file :
Total time taken in mili seconds :::: 19769

10000 tuples in each input file :
Total time taken in mili seconds :::: 36448

20000 tuples in each input file :
Total time taken in mili seconds :::: 152006
