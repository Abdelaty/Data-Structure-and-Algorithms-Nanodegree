# Problem 7 

It is similar to __problem 5__, except for the _edge cases_, like "root handler", and working with a __hierarchy of 
web pages__ instead of strings. This problem is focused on the development of the of a __trie__ a data structure 
derived from a _tree_, suited for a good ratio between _time and space_ complexity.

### Time and Space complexity
For the __trie__, time complexity of **searching and inserting** from a trie depends on the length of the path **n**
that’s being searched for, inserted, making the runtime of these operations __O(n)__. Looking into the space 
complexity of a __trie__, the worst case, would be when we have a path (or paths), with no common folders between them,
hence having, a node for each _path block_ (path between forward slashes). Resulting in a _space complexity_ of  
__O(n)__.
