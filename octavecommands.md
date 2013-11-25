
1. Change prompt:  PS('>> ');

2a. Change working directory:	   cd '/path/to/directory' 
2b. Current directoyr listing:     dir | ls
2c. Remove direcroty: 		   rmdir
2d. Create directory:		   mkdir

3. Elementary operatins:  5+6 | 3-2 | 1/2 | 2^6

4. Comments:  %

5a. True False operations:  1==2  %o/p- false
5b. Not Equals operations:  1~=2  % ~=  -->> Not equals to

6a. AND:        1 && 0
6b. OR:		1 || 0
6c. XOR:	xor(1,0)

7. Variable Assignment:  a = 3;  |  b = 'hi' | c = 3>=1;

8a. Display variables:  disp(a) 
8b. Formatted display:  disp(sprintf('2 decimals places: %0.2f', a))
8c. Formatted display:  disp(sprintf('6 decimals places: %0.6f', a))

9a. Change default format to Long:  format long
9b. Change default format to Short: format short

10a. Matrices:  a = [1,2;3,4;5,6;7,8;9,10]  % a is a 3*3 matrix
10b. Vectors:  cv = [10;20;30]  % v is a 3*1 column vector
10c. Vectors:  rv = [1,2,3]  % rv is a Row Vector

11a. Step-Sized initiation:  v = [1: 0.5 : 2]  % Initiate Row-vector, starting from 1 ending at 2, 0.5 as stepsize.
11b. Step-Sized initiation:  p = [1:10]  % Initate row-vector, assuming 1 as step size.

12a. Matrix with all elements 1: ones(3,3)  % Creates a 3*3 matrix with all elements as 1.
12b.  v = 2*ones(3,3)  %  Same as v = [2,2,2;2,2,2;2,2,2]

13a. zeros(3,3)  % Creates a 3*3 matrix with all ements 0.
13b. zeros(1,3)  % Creates a row-vector with all elements 0.

14a. Random Matrix:  rand(3,3)  % Create a 3*3 matrix with random values taken from a UNIFORM distribution.
14b. Random Matrix:  randn(3,3) % Create a 3*3 matrix with random values taken from a NORMAL distribution (mean =0 || 
     variance =1 )
14c. Random Matrix:  randi(3,3)  % Create a 3*3 matrix with random INTEGER values.

15. Square Root calculation:  sqrt(4) | sqrt(13)

16a. w = -6 + sqrt(10)*(randn(1,10));  
16b. Plotting Histograms:  hist(w)  % Plot histogram of w using the default bin size - 10.
16c. Plotting Histograms:  hist(w,15)  % Plot histograms of w using bin size as 15.

17. Identity Matrix:  eye(3)   % Create a 3*3 Identity matrix.




