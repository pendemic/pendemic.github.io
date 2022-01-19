
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
</body>
</html>