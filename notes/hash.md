# Hashing

## Hashing and Chaining
## Universal Hashing
## Perfect Hashing
## Cackoo Hashing

## Interview Questions
1. Given $$10^6$$ strings(search record), how can you quickly find top-k popular strings? 
  * Ans: In general case, we can use a hash map to keep tracks of the occurence of each string. And then use a min-heap to maintain k records. 
  * Analysis: This takes O(n) space and O(nk) time. But if popular strings are really popular, we don't really need O(n) space.
2. What is a good size for hash table? How do they choose hash table size? 
  * Ans: Prime number. Reason ....
