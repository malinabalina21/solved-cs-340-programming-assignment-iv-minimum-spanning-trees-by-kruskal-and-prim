Download Link: https://assignmentchef.com/product/solved-cs-340-programming-assignment-iv-minimum-spanning-trees-by-kruskal-and-prim
<br>
<strong>CS 340 Programming Assignment IV: </strong>

<strong>Minimum Spanning Trees by Kruskal and Prim </strong>




<strong>Description:</strong> You are to implement <strong>Kruskal’s Algorithm </strong>and <strong>Prim’s Algorithm </strong>for finding Minimum Spanning Trees (MSTs) of undirected positively weighted graphs adhering to the specifications detailed below.




<strong>I/O Specifications: </strong>You will read your input graph from an input file named <strong>graphin.txt </strong>of the following adjacency list representation where each x<sub>ij</sub> is the j’th neighbor of vertex i (vertex labels are 1 through n) and w<sub>ij</sub> is the weight of the edge between vertices i and X<sub>ij</sub>:

1: x11 w11 x12 w12 x13 w13… 2: x21 w21 x22 w22 x23 x23 …

.

. n: xn1 wn1 xn2 wn2 xn3 wn3 …

Your output from Kruskal’s algorithm will be to a file named <strong>kruskalout.txt</strong>, and your output from Prim’s algorithms will be to <strong>primout.txt</strong>, both of the following edge list form:

x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub>

.

. xn-1 yn-1

This is just a list of the n-1 edges involved in the computed MST in the order of computation.




<strong>Algorithmic specifications: </strong>

Your algorithm must run in O(E log V) time on any input graph.  Therefore, you must use the adjacency list representation for input processing.  E.g., you may implement your adjacency list as an array of linked lists or an array of vectors. <strong>For Kruskal’s algorithm</strong>, you must sort the edges by weight using an efficient (O(m log m)) sorting algorithm that you already implemented.  In growing your forest of trees, you must implement an efficient Disjoint Set structure in which both the union operation and the find operation take O(log n) time, using either union-by-size or union-by-depth heuristics, stated in comments.  <strong>For Prim’s algorithms, </strong>you have already partially implemented a Heap and need to complete the implementation for a min-Heap including heap insertion, decrease key, and deletion, being careful to be able to access the heap positions from the adjacency list and vice versa.


