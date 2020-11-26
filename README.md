# Coding-Interview-101
> Author: @xianzhez
> 
> Last updated: 2020.11.25
> 
> 
> Remark: 
> 
> For data structures and algorithms in this document
> 
> - in bold: you must know the concept and complexity, and can implement in real code.
> - normal: you should know the concept and complexity, but pseudo-code is fine.
> - in italic:  you should know the general idea. If you encounter such a question for entry-level position, that company might not be hiring actively.

## Preface

This post is summarizing the data structure and algorithm fundamentals you might need in a coding interview and the corresponding implementations in different languages (Currently Python, Java, and C++). 

You may or may not know some of them. It's totally fine. You could easily find videos, blogs, and source code about these data structures and algorithms online.

I tried to make it accurate and correct. But I might be still missing something important or writing something wrong. If you find any mistake or have good advice, you are welcome to contact me. If you find it useful, welcome to star, fork, and share this repo. Please also provide the reference if you are going to refer to this repo.

Coding classic algorithms may not represent your actual ability and specialization. Don't feel discouraged if you cannot solve it in limited time or fail an interview. It takes some time!

I will keep updating this doc and make it more helpful. I hope everyone could land a dream job eventually. Keep coding!

## Prerequisite
1. Learn a programming language;
2. Learn data structures and APIs;
3. Understand the underlying implementation of data structures;
4. Understand complexity analysis;
5. Learn classical algorithms and advanced data structures;

## Language
- C++: [cplusplus.com - The C++ Resources Network](https://www.cplusplus.com/)
- Python: [Python Tutorial](https://docs.python.org/3/tutorial/)
- Java: [Java Documentation](https://docs.oracle.com/javase/tutorial/)
## Data Structures
> - Cheatsheet(ALGS4)(Java): [Algorithms and Data Structures Cheatsheet](https://algs4.cs.princeton.edu/cheatsheet/)  
> - [Big-O Algorithm Complexity](https://www.bigocheatsheet.com/)  


> Python: [5. Data Structures — Python 3.8.6 documentation](https://docs.python.org/3/tutorial/datastructures.html#)[Common Python Data Structures (Guide) – Real Python](https://realpython.com/python-data-structures/)  
> Java: [Lesson: Interfaces (The Java™ Tutorials > Collections)](https://docs.oracle.com/javase/tutorial/collections/interfaces/index.html)  
> C++: [Containers - C++ Reference](https://www.cplusplus.com/reference/stl/)  

### Basic
* **Array**: 

> Python: list  
> Java: ArrayList  
> C++: vector  

* **LinkedList**: 

> Python: list or customized  
> Java: LinkedList   
> C++: std::list

* **HashTable**: 

> Python: dict(), collections.defaultdict()   
> Java: HashMap, TreeMap (Heap)  
> C++: unordered_map, map  

* **HashSet**

> Python: set()  
> Java: HashSet(), TreeSet()  
> C++: unordered_set, set, multi_set  

### Advanced
* **Tree**
* **Graph**
* **Stack**

> Python: list, deque  
> Java: Stack  
> C++: std::stack

* **Deque**

> Python: collections.deque()  
> Java: LinkedList, ArrayDeque
> C++: std::deque

* **PriorityQueue** (heap)

> Python: heapq, collections.PriorityQueue (thread safe)  
> Java: PriorityQueue  
> C++: std::priority_queue

* BinarySearchTree (map)

> Python: None (try to use heapq)  
> Java: TreeMap  
> C++: std::map

* BinarySearchTree (set)

* Trie: a map of key, map pairs; 

> - `T = lambda: collections.defaultdict(T)`
> - [Implement Trie (Prefix Tree) - LeetCode](https://leetcode.com/problems/implement-trie-prefix-tree/)

* UnionFind

### Ultimate
* *Red-black tree*
* *KD-Tree*
* *B-tree*
* *Segment Tree*

## Algorithms

> Cheatsheet(ALGS4) (Java): [Algorithms and Data Structures Cheatsheet](https://algs4.cs.princeton.edu/cheatsheet/)  

### Basics
* **DFS**
* **BFS**
* **BackTracking**
* **Binary Search**
* **Two pointers**
* Fast and slow pointers
* Reverse!

### Advanced
* **Topological sort**
* Greedy: e.g. Huffman coding
* Divide and Conquer
* Cycle detection in undirected graph
* Cycle detection in directed graph
* UnionFind
* Find SCC in directed Graph
* Lowest Common Ancestor 
	* [Lowest Common Ancestor of a Binary Tree - LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)[Lowest Common Ancestor Binary Tree - YouTube](https://www.youtube.com/watch?v=13m9ZCB8gjw&list=RDCMUCZLJf_R2sWyUtXSKiKlyvAw&index=8&frags=pl%2Cwn)
* Dijkstra: single source shortest path, O(nlogn + m )
* Bellman-Floyd: single source with negative weights, O(mn)
* Floyd-Warshall: all pairs shortest path; O(n^3)
* Reservoir Sampling
* KMP [Implement strStr() - LeetCode](https://leetcode.com/problems/implement-strstr/)
* *Manacher*
* *Morris*

### Ultimate
* *Minimum Spanning Tree: Prim’s, Kruskal*
* *minimum s-t cut: Ford-Fulkerson*
* *global min cut: Karger’s, Karger Stein*


### Dynamic Progamming
> Recipe for DP:  
> 1. Identify optimal substructure  
> 2. Find a recursive formulation for the optimal solution  
> 3. Use dynamic programming to find optimal solution  
> 4. If needed, keep track of some additional info so that the algorithm from step 3 can find the actual solution  

Classical Problems:

* LCS: longest common subsequence [Longest Common Subsequence - LeetCode](https://leetcode.com/problems/longest-common-subsequence/)
* unbounded knapsack
* 0/1 knapsack

LeetCode
LC322M: [Coin Change - LeetCode](https://leetcode.com/problems/coin-change/)

Complexity: reduce time complexity from exponential with brutal force to polynomial. 

## Resources
### Blogs and Repos
> 1. [GitHub - Tech-Interview-Cheat-Sheet](https://github.com/TSiege/Tech-Interview-Cheat-Sheet): An interview cheatsheet.
> 2. [Data Structures - GeeksforGeeks](https://www.geeksforgeeks.org/data-structures/): data structure basics  
> 3. [fucking-algorithm](https://github.com/labuladong/fucking-algorithm/tree/english): algorithms (available in both English and Chinese)
> 4. [fuck-coding-interviews](https://github.com/vinta/fuck-coding-interviews): data structure and algorithms implementation, as well as solutions for leetcode questions sorted by categories.

### Videos
> These videos and Youtuber might be helpful.

> You can also take some online courses or watch some famous courses online to learn data structures and algorithms systematically if you have enough time. This might be time consuming but useful. Such as CS106B@Stanford, CS161@Stanford, 6.006@MIT, etc.

> Some textbooks you can refer to but not required:
> 
> - [Introduction to Algorithms](https://www.google.com/books/edition/Introduction_to_Algorithms/i-bUBQAAQBAJ?hl=en&gbpv=0)
> - [Algorithms](https://algs4.cs.princeton.edu/home/) 

### Algorithms
- @[Tushar Roy - Coding Made Simple](https://www.youtube.com/user/tusharroy2525/featured)
	- [Graph Algorithms @ Tushar Roy - Coding Made Simple](https://www.youtube.com/playlist?list=PLrmLmBdmIlpu2f2g8ltqaaCZiq6GJvl1j): I found these videos very useful to understand and implement graph algorithms. Tushar also provide the source code.

	- [Dynamic Programming @ Tushar Roy - Coding Made Simple](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)

- @[Abdul Bari](https://www.youtube.com/channel/UCZCFT11CWBi3MHNlGf019nw/playlists)
	- [Algorithms](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O): most of algorithms mentioned in this blog are covered.

### Interview tips
- @[Clément Mihailescu](https://www.youtube.com/channel/UCaO6VoaYJv4kS-TQO_M-N_g)
	- [Google Coding Interview With A College Student](https://www.youtube.com/watch?v=3Q_oYDQ2whs)
	- [Google Coding Interview With A High School Student](https://www.youtube.com/watch?v=qz9tKlF431k&t=4s)

- @[TechLead](https://www.youtube.com/channel/UC4xKdmAXFh4ACyhpiQ_3qBw)
	- [How to solve coding interview problems ("Let's leetcode") @ TechLead](https://www.youtube.com/watch?v=dIrS31CCITM)

### Takeaway

#### Before the interview
- Practice on some platforms such as LeetCode, Google KickStart, HackerRank;
	- LeetCode Premium is very useful, especially you can filter questions with tags and companies, and sort problems by frequency. You can consider
	- Participating in the weekly contest on LeetCode is also a good way to practice interivew.
- Find someone to do mock interview.

#### In the interview
- Correctness matters, find a workable solutions at least.
- Time matters, spending too much on a simple solution you have known is not a good option.
- Communication matters, think loud and let the interviewer know what you are thinking about. Then the interviewer can know how to give you hints.
- Handle edge cases, you can skip some parts handling edge cases and complete them later, but you must let the interviewer know that you have noticed these edge cases. You can add some TODOs or move it to a function to implement later.
- Time complexity and space complexity are necessary. Even the interviewer forgets to ask you about the complexity analysis, you should address them. Because it is an important part of the feedback the interviewer will submit.

