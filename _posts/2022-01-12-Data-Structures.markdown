
<html>
<head>
    <meta charset="utf-8" />
    <title>Data Structures Notes</title>
</head>
<body>
<p><span style="font-weight: 400; font-size: 20px;">Data Structures</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Currently studying a data structures video and will be adding more notes as I learn.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A data structure is a way of organizing data so it can be used efficiently.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">An abstract data type is an abstraction of a data structure which provides only the interface to which a data structure must adhere to. EX: List, Queue, Map</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Arrays</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A static array is a fixed length container containing n elements indexable from the range [0,n-1].</span></p>
<p><span style="font-weight: 400;">Uses: Storing and accessing sequential data, temporarily storing objects, used by IO routines as buffers, Lookup tables and inverse lookup tables, can be used to return multiple values from a function, used in dynamic programming to cache answers to subproblems.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Linked Lists</span></p>
<p><span style="font-weight: 400;">A linked list is a sequential list of nodes that hold data which point to other nodes also containing data. Last node always has a null reference.&nbsp;</span></p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used in many List, Queue and stack implementation</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Creating circular lists</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Model real world objects such as trains</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used in separate chaining, which is present certain Hashtable implementations to deal with hashtag collisions</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Often used in the implementation of adjacency lists for graphs</span></li>
</ul>
<p><span style="font-weight: 400;">Head: The first node in a linked list</span></p>
<p><span style="font-weight: 400;">Tail: The last node in a linked list</span></p>
<p><span style="font-weight: 400;">Pointer: Reference to another node</span></p>
<p><span style="font-weight: 400;">Node: An object containing data and pointers</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Singly vs Doubly Linked Lists</span></p>
<p><span style="font-weight: 400;">Singly: Only hold a reference to the next node</span></p>
<p><span style="font-weight: 400; color: green;">Uses less memory, simpler implementation</span><span style="font-weight: 400;">. </span><span style="font-weight: 400; color: red;">Cannot easily access previous elements.</span></p>
<p><span style="font-weight: 400;">Doubly: Each node holds a reference to the next and previous node.</span></p>
<p><span style="font-weight: 400; color: green;">Can be traversed backwards.</span> <span style="font-weight: 400; color: red;">Takes 2x memory.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Stack</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A stack is a one-ended linear data structure which models a real world stack by having two primary operations, push and pop.</span></p>
<p><span style="font-weight: 400;">Pop - removes top element from stack</span></p>
<p><span style="font-weight: 400;">Push - Adds element to top of stack</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used by undo mechanisms in text editors</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used in compiler syntax checking for matching brackets and braces</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Can be used to model a pile of books or plates</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used behind the scenes to support recursion by keeping track of previous function calls</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Can be used to do a Depth First Search (DFS) on a graph</span></li>
</ul>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Queue</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A Queue is a linear data structure which models real world queues by having two primary operations, enqueue and dequeue.</span></p>
<p><span style="font-weight: 400;">Enqueue - Adding elements to the back - Also called Adding, Offering</span></p>
<p><span style="font-weight: 400;">Dequeue - Removing elements from the front - Also called Polling, Removing</span></p>
<p><span style="font-weight: 400;">Peeking - Looking at value at the front of the queue without removing it</span></p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Any waiting line models a queue, for example a lineup at the movie theatre</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Can be used to efficiently keep track of the x most recently added elements</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Web server request management where you want first come first serve</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Breadth First Search (BFS) graph traversal</span></li>
</ul>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Priority Queues</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A priority queue is an Abstract Data Type that operates similar to a normal queue except that each element has a certain priority. The priority of the elements in the priority queue determine the order in which elements are removed from the PQ.</span></p>
<p><span style="font-weight: 400;">Note: Priority Queues only support comparable data, meaning the data inserted into the priority queue must be able to be ordered in some way either from least to greatest or greatest to least. This is so that we are able to assign relative priorities to each element.</span></p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used in certain implementations of Dijsktra&rsquo;s Shortest path algorithm</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Anytime you need the dynamically fetch the &lsquo;next best&rsquo; or &lsquo;next worse&rsquo; element</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used in Huffman coding (which is often used for lossless data compression)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Best First Search (BFS) algorithms such as A* use PQs to continuously grab the next most promising node.</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Used by Minimum Spanning Tree (MST) algorithms</span></li>
</ul>
<p><span style="font-weight: 400;">Implementation</span></p>
<p><span style="font-weight: 400;">Priority Queues are usually implemented with heaps since this gives them the best possible time complexity.</span></p>
<p><span style="font-weight: 400;">The Priority Queue (PQ) is an Abstract Data Type (ADT), hence heaps are not the only way to implement PQs. As an example we could use an unsorted list, but this would not give us the best possible time complexity</span></p>
<p><span style="font-weight: 400;">Types of Heaps: Binary, Fibonacci, Binomial, Pairing, etc</span></p>
<p><br /><br /></p>
<p><span style="font-weight: 400;">Heap</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A heap is a tree based data structure (DS) that satisfies the heap invariant (also called heap property): If A is a parent node of B then A is ordered with respect to B for all nodes A, B in the heap.</span></p>
<p><span style="font-weight: 400;">Max heap - Parent node is always greater than its children</span></p>
<p><span style="font-weight: 400;">Min heap - Parent node is always less than its children</span></p>
<p><span style="font-weight: 400;">Binary - a binary tree that supports the heap invariant. In a binary tree every node has exactly 2 children.</span></p>
<p><span style="font-weight: 400;">Complete binary tree - at every level, except possibly the last is completely filled and all nodes are as far left as possible. Very important to maintain because it gives us an insertion point.</span></p>
<p><span style="font-weight: 400;">Representation</span></p>
<p><span style="font-weight: 400;">Can be represented by an array. Last index is the insertion point.</span></p>
<p><span style="font-weight: 400;">Let i be the parent node index</span></p>
<p><span style="font-weight: 400;">Left child index: 2i + 1</span></p>
<p><span style="font-weight: 400;">Right child index: 2i + 2</span></p>
<p><span style="font-weight: 400;">(zero based)</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Union Find (Disjoint set)</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Union Find is a data structure that keeps track of elements which are split into one or more disjoint sets. It has two primary operations - find and union</span></p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Kruskal&rsquo;s minimum spanning tree algorithm</span></li>
</ul>
<p><span style="font-weight: 400;">Minimum spanning tree is a subset of the edges which connect all vertices in the graph with the minimal total edge cost</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Grid percolation</span></li>
</ul>
<p><span style="font-weight: 400;">Finding path from top of grid to bottom or vice versa</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Network connectivity</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Least common ancestor in trees</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Image processing</span></li>
</ul>
<p><span style="font-weight: 400;">Operations</span></p>
<p><span style="font-weight: 400;">Find - To begin using Union Find, first construct a bijection (a mapping) between your objects and the integers in the range [0,n) - Allows us to construct an array based union find</span></p>
<p><span style="font-weight: 400;">To find which component a particular element belongs to find the root of that component by following the parent nodes until a self loop is reached (a node who&rsquo;s parent is itself)</span></p>
<p><span style="font-weight: 400;">Unify - To unify two elements find which are the root nodes of each component and if the root nodes are different make one of the root nodes be the parent of the other.</span></p>
<p><span style="font-weight: 400;">Path Compression</span></p>
<p><span style="font-weight: 400;">Pointing all nodes and their parent nodes directly to the root node.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">&nbsp;Binary Trees and Binary Search Trees (BST)</span></p>
<p><span style="font-weight: 400;">A tree is an undirected graph which satisfies any of the following definitions:</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">An acyclic connected graph</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">A connected graph with N nodes and N-1 edges</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">A graph in which any two vertices are connected by exactly one path</span></li>
</ul>
<p><span style="font-weight: 400;">If we have a rooted tree then we will want to have a reference to the root node of our tree</span></p>
<p><span style="font-weight: 400;">Child - Is a node extending from another node</span></p>
<p><span style="font-weight: 400;">Parent - Is the inverse of this</span></p>
<p><span style="font-weight: 400;">Root node has no parent, parent of the root node is itself</span></p>
<p><span style="font-weight: 400;">Leaf node - A node with no children</span></p>
<p><span style="font-weight: 400;">Subtree - A tree entirely contained within another tree - Usually denoted with triangles</span></p>
<p><span style="font-weight: 400;">Binary Search Tree (BST)&nbsp;</span></p>
<p><span style="font-weight: 400;">A binary search tree is a binary tree that satisfies the BST invariant: left subtree has smaller elements and right subtree has larger elements.</span></p>
<p><span style="font-weight: 400;">Uses</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Implementation of some map and set ADTs</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Red Black Trees</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">AVL Trees</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Splay Trees</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Etc.</span></li>
</ul>
<p><span style="font-weight: 400;">Used in the implementation of binary heaps</span></p>
<p><span style="font-weight: 400;">Syntax trees (used by compiler and calculators)</span></p>
<p><span style="font-weight: 400;">Treap - a probabilistic DS (uses a randomized BST)</span></p>
<p><span style="font-weight: 400;">Adding elements to a BST</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Recurse down left subtree (&lt; case)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Recurse down right subtree (&gt; case)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Handle finding a duplicate value (= case)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Create a new node (found a null leaf)</span></li>
</ul>
<p><span style="font-weight: 400;">Removing elements from a BST</span></p>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Find the element we wish to remove (if it exists) 4 things can happen:</span></li>
</ol>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">We hit a null node at which point we know the value does not exist within our BST</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Comparator value equal to 0 (found it!)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Comparator value less than 0 (the value, if it exists, is in the left subtree)</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Comparator value greater than 0 (the value, if it exists, is in the right subtree)</span></li>
</ul>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Replace the node we want to remove with its successor (if any) to maintain BST invariant. 4 Cases</span></li>
</ol>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Node to remove is a leaf node - Just remove node</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Node to remove has a right subtree but no left subtree</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Node to remove has a left subtree but no right subtree</span></li>
</ul>
<p><span style="font-weight: 400;">Successor of the node we are removing will be the root node of the left/right subtree</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Node to remove has both a left subtree and a right subtree</span></li>
</ul>
<p><span style="font-weight: 400;">Successor can be largest value in left tree or smallest value in right</span></p>
<p><span style="font-weight: 400;">Tree Traversals</span></p>
<p><span style="font-weight: 400;">Preorder - Preorder prints before the recursive calls</span></p>
<p><span style="font-weight: 400;">Inorder - Inorder prints between the recursive calls - prints values increasing inorder</span></p>
<p><span style="font-weight: 400;">Postorder - Postorder prints after the recursive calls</span></p>
<p><span style="font-weight: 400;">Level order - Print the nodes as they appear one layer at a time</span></p>
<p><span style="font-weight: 400;">To obtain this ordering we want to do a Breadth First Search (BFS) from the root node down to the leaf nodes</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Hash Tables</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A Hash table (HT) is a data structure that provides a mapping from keys to values using a technique called hashing. Key-Value pairs keys must be unique but values can be repeated.</span></p>
<p><span style="font-weight: 400;">HT are often used to track item frequencies.</span></p>
<p><span style="font-weight: 400;">The key-value pairs you can place in a HT can be of any type not just strings and numbers but also objects</span></p>
<p><span style="font-weight: 400;">Hash function H(x) - function that maps a key &lsquo;x&rsquo; to a whole number in a fixed range. indexes to array</span></p>
<p><span style="font-weight: 400;">We can also define hash functions for arbitrary objects such as strings, lists, tuples, multi data objects, etc</span></p>
<p><span style="font-weight: 400;">Hash collision - Is when two objects x,y hash to the same value (H(x) = H(y))</span></p>
<p><span style="font-weight: 400;">To solve this use separate chaining and open addressing</span></p>
<p><span style="font-weight: 400;">Separate chaining - deals with hash collisions by maintaining a data structure (usually a linked list) to hold all the different values which hashed to a particular value.</span></p>
<p><span style="font-weight: 400;">Each position of array is a linked list.</span></p>
<p><span style="font-weight: 400;">Open addressing - deals with hash collisions by finding another place within the hash table for the object to go by offsetting it from the position to which it hashed to.</span></p>
<p><span style="font-weight: 400;">Key value pairs are stored in the table itself as opposed to a data structure</span></p>
<p><span style="font-weight: 400;">Uses a probing sequence to find next unoccupied slot</span></p>
<p><span style="font-weight: 400;">Probing Sequences - Linear, Quadratic, Double Hashing, Pseudo random number generator</span></p>
<p><span style="font-weight: 400;">Can be caught in an infinite loop fix by creating probing functions that don&rsquo;t produce cycles.</span></p>
<p><span style="font-weight: 400;">Linear Probing(LP)</span></p>
<p><span style="font-weight: 400;">A probing method which probes according to a linear formula</span></p>
<p><span style="font-weight: 400;">P(x) = ax + b where a != 0, b are constants</span></p>
<p><span style="font-weight: 400;">To produce a full cycle a and modulo N must be relatively prime</span></p>
<p><span style="font-weight: 400;">Relatively prime - Greatest common denominator is equal to 1</span></p>
<p><span style="font-weight: 400;">Quadratic Probing (QP)</span></p>
<p><span style="font-weight: 400;">A probing method which probes according to a quadratic formula</span></p>
<p><span style="font-weight: 400;">P(x) = ax^2 + bx + c where a,b,c are constants and a != 0 (otherwise we have linear probing)</span></p>
<p><span style="font-weight: 400;">Randomly selected QP functions have the issue that they easily produce short cycles.</span></p>
<p><span style="font-weight: 400;">Full Cycle popular approaches</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">P(x) = x^2, keep table size a prime number &gt; 3 and also keep load factor &lt;= &frac12;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">P(x) = (x^2 + x)/2 and keep the table size a power of two</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">P(x) = (-1^x)*x^2 and keep the table size a prime N where N = 3 mod 4</span></li>
</ul>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Double Hashing (DH)</span></p>
<p><span style="font-weight: 400;">Is a probing method which probes according to a constant multiple of another hash function</span></p>
<p><span style="font-weight: 400;">P(k,x) = x*H2(k), where H2(k) is a second hash function&rsquo;</span></p>
<p><span style="font-weight: 400;">H2(k) must hash the same type of keys as H1(k)</span></p>
<p><span style="font-weight: 400;">Since DH reduces to linear probing at runtime we may end up with a linear probing function that causes a infinite cycle</span></p>
<p><span style="font-weight: 400;">To fix the issue of cycles pick the table size to be a prime number and also compute the value of delta. If delta = 0 you are guaranteed to be stuck in a cycle. If this happens set delta = 1</span></p>
<p><span style="font-weight: 400;">To resize table with DH double the table size then find the next prime number above it</span></p>
<p><span style="font-weight: 400;">Removing from open addressing</span></p>
<p><span style="font-weight: 400;">Tombstones - Count as a filled slot after removing a key so that the search doesn&rsquo;t stop with a null value.</span></p>
<p><span style="font-weight: 400;">Lazy deletion - An optimization we can do is replace key with earliest tombstone we encountered next time the key is looked up it will be much faster.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Fenwick Tree (Binary Indexed Tree)</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A Fenwick Tree is a data structure that supports sum range queries as well as setting values in a static array and getting the value of the prefix sum up some index efficiently.</span></p>
<p><span style="font-weight: 400;">Unlike a regular array, in a Fenwick tree a specific cell is responsible for other cells as well.</span></p>
<p><span style="font-weight: 400;">The position of the least significant bit (LSB) determines the range of responsibility that cell has to the cells below itself.</span></p>
<p><span style="font-weight: 400;">All odd cells have their LSB in the first position so they are only responsible for themselves</span></p>
<p><span style="font-weight: 400;">1 based</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Suffix Array</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">A suffix is a substring at the end of a string of characters.</span></p>
<p><span style="font-weight: 400;">A suffix array is an array which contains all the sorted suffixes of a string</span></p>
<p><span style="font-weight: 400;">The actual suffix array is the array of sorted indices - lexicographically</span></p>
<p><span style="font-weight: 400;">The suffix array provides a space efficient alternative to a suffix tree which itself is a compressed version of a trie.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">The Longest Common Prefix array (LCP)</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Example: Find the LCP array of the string &lsquo;ABABBAB&rsquo;</span></p>
<p><span style="font-weight: 400;">Begin by constructing the suffix array</span></p>
<p><span style="font-weight: 400;">The LCP array is an array in which every index tracks how many characters two sorted adjacent suffixes have in common</span></p>
<p><span style="font-weight: 400;">LCP[0] is undefined but it is fine to set to 0</span></p>
</body>
</html>