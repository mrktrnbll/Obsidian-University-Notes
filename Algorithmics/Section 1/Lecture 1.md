---
tags:
  - Algs
  - Lecture
---
Lecture 1 | 28/09/23
:-- | --

---
## Section 1 - Sorting and Tries

### Recap
- O(n^2) Selection, bubble, Instertion sort
- O(nlogn) merge, heap
- O(nlogn) quicksort best case no worse than O(n^2)
	
### Proof O(n) Not possible
Can you have O(n) average case sorting alogrithm?
	> If you take a binary tree, each exec of alg is the path from root node to leaf i.e. the worst case time complexity is no better than O(h) where h is the height of the tree
	> The complete possibilities of leaf nodes is n!
	> The number of leaf node is ${\le 2^{h+1}-1}$ 
	This then leaves us with ${n! \ge 2^{h+1}-1 \ge 2^{h+1}}$  
	Taking log of both sides leaves ->
		${h+1 \ge \log_2 n!}$
				 ${>\log_2 n/2^{n/2}}$
				 ${= n/2 \log_2 n/2}$
				 ${= n/2 \log_2 n - n/2 \log_2 2}$
				 ${= n/2 \log_2n - n/2}$
	Which then makes the time complexity  
		O(${n \log n}$)
	Since n/2 can be made n as division by a constant has no affect in calculating O(n)

### Radix Sorting 
Sorting techniques uses something other than comparison to achieve O(n)
	- #Vague numbers are made to bit values
	- the number of bit values are named m
	- they are given a buckets

### Tries (reTRIEval)
