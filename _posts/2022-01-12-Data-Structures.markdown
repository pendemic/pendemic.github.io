
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
</body>
</html>