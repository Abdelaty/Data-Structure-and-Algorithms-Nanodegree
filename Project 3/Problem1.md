# Problem 1
The principle of this algorithm is to implement a _variance of the binary search_, due to the required __time 
complexity__. This time, though, instead of counting with an already sorted array, we use the _natural consecution_ to
use as our __imaginary array__; the implementation relies on dividing the search space in two parts and checking at 
each time if the __mid point power of 2__ is bigger or smaller than the given number (as in a dictionary, is the found 
word, bigger or smaller than our goal). Additionally, there is the inclusion of a little _optimization trick_, this is
the fact that the __square root__ of a natural number (starting from 2) is _half or less_, thus giving us a __speed 
boost_ by starting with `end = number // 2`.

### Time and Space complexity:
In this case time complexity is __O(log(n))__, as we transverse the _hypothetically ordered natural's number list_ by 
using a __binary search approach__. As for the space complexity, it is __independent of the input__, requiring solely 
pointers to different array locations; __O(1)__.
