# Problem 3

This problem, as stated to be solved in _time complexity_ of __O(n*log(n))__, has given the clue to be tackled by a 
variation of the __merge sort__ algorithm. Indeed, it is a _merge sort_ algorithm, except for the particular treatment 
if gives to the comparison of results coming from the previous recursion, if we are on the _first level_ of the
recursion. In this case, it does the _comparison_, as usual, but then starts saving the results on 
__alternative lists__, which are then returned as the results. 

The usage of this _alternative list saving_ is due to the fact that having the list perfectly sorted, if we start from
the index[0] and give alternatively a value to each list, occupying this value an increasing digit position, we 
__always__ obtain a combination that satisfies the condition of having a __maximum sum of two numbers__ and __maximum a
digit of difference between them__.  

### Time and Space complexity 
As the base of the algorithm is the __merge sort__, having a time complexity of __O(n*log(n))__, and there have been no
substantial modifications to the algorithm; just the addition of __O(1)__ operations, the time complexity remains 
_equal_. As for the space complexity, if we hold the assumption that python gets automatically rid of each previous 
step auxiliary created arrays, then the space complexity is of __O(n)__ (we have always arrays tat amount to the 
length of the input array).
