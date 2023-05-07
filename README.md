Download Link: https://assignmentchef.com/product/solved-java-program-which-reads-a-directed-graph-g
<br>
There are two standard ways to represent a graph <em>G=(V,E)</em>, where <em>V</em> is a set of vertices and <em>E</em> is a set of edges; Adjacency list representation and Adjacency matrix representation.

An adjacency-list representation consists of an array <em>Adj[|V|]</em> of |V| lists, one for each vertex in <em>V</em>. For each <em>u∈V</em>, the adjacency list <em>Adj[u]</em> contains all vertices <em>v</em> such that there is an edge <em>(u,v)∈E</em>. That is, <em>Adj[u]</em> consists of all vertices adjacent to <em>u</em> in <em>G</em>.

An adjacency-matrix representation consists of <em>|V|</em> × <em>|V|</em> matrix <em>A=aij</em> such that <em>aij=1</em> if <em>(i,j)∈E</em>, <em>aij=0</em> otherwise.

Write a java program which reads a directed graph <em>G</em> represented by the adjacency list, and prints its adjacency-matrix representation. <em>G</em> consists of <em>n(=|V|)</em> vertices identified by their IDs <em>1,2,..,n</em> respectively.

Input

In the first line, an integer <em>n</em> is given. In the next nn lines, an adjacency list <em>Adj[u</em>] for vertex <em>u</em> are given in the following format:

<em>u k v1 v2 … vk</em>

<em>u</em> is vertex ID and <em>k</em> denotes its degree. <em>vi</em> are IDs of vertices adjacent to <em>u</em>.

Output

As shown in the following sample output, print the adjacent-matrix representation of <em>G</em>. Put a single space character between <em>aij</em> .

Sample Input

<pre>41 2 2 42 1 43 04 1 3</pre>

Sample Output

<pre>0 1 0 10 0 0 10 0 0 00 0 1 0</pre>