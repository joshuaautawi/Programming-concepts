
# BIG O NOTATION
 
 First of all ,Asymptotic Notation is languages that allow us to analyze an algorithm's running time by identifying its behavior as the input size for the algorithm increases.
 Asymptotic notation describes the algorithm efficiency and performance in a meaningful way. 

 
 Big O notation is a mathematical notation that describe 
 limited behaviour of a function. In computer science , 
 big O notation used for calculate the run time or space 
 requirement as the input size grows.
 
 In short , Big O Notation is how long the algorithma takes to run
  depending how big the input data . And this usually takes
  the worst case scenario.

### Why Big O Notation is Important ?
Big O notation help developer being aware of the effeciency
of the algorithm so they can create apps with great performance.


Big O Notation generally classified as :

- O(1) - Constants => there is only 1 step for this case. The output is always 1 output and do not do iteration .
- O(n) - Linear => number of step depend on how many input size. The output is depend on the n (input) , example is simple looping.
- O(n²) - Quardractic => number step required is the square root of the input size . Example is bubbleSort
- O(log n) - Logarithmic => Holy grail for search/sort algorithm.They are usually the most efficient when dealing with large collection. This algorithm never look for all input , but it eliminate large amount of input of each step. The step depend more from how complicated the algorithm itself . Example : quickSort , mergeSort.
- O(n log n) - Linearithmic => Big problem broken into small subproblem , solving them independenly and combine them.The step more depend on the complexity of the problem . Example : mergeSort.
- O(2^n) - Exponential => Should be avoid , the step depend on the algorithm and double it for each step of the algorithm. Example : Recursive
