# Problem 5
This problem is focused on the development of the of a __trie__ a data structure derived from a _tree_, suited for a
 good ratio between _time and space_ complexity.

### Time and Space complexity
For the __trie__, time complexity of **searching and inserting** from a trie depends on the length of the word **a** 
that’s being searched for, inserted, and the number of total words, **n**, making the runtime of these operations
 __O(a*n__). Looking into the space complexity of a __trie__, the worst case, would be when we have a word (or words),
 with no common characters between them, hence having, a node for each letter. Resulting in a _space complexity_ of 
 __O(n)__.
