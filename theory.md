### Breadth First Search Algorithm

##### Starts at some an arbitrary node of a graph and explores the neighbour node first before moving to the next level neighbours.Used for graphs without loop.All edges have same weight or no weight.

<ol>
<li> Take an Empty Queue.</li>
<li> Select a starting node (visiting a node) and insert (enqueue) it into the Queue.</li>
<li>Provided that the Queue is not empty, extract the node from the Queue and insert its child nodes  into the Queue.</li>
<li>Add extracted node to the path </li>
</ol>  

## Example 

<p align="center">
 Initialize the queue.
<img src="images/BFS1.png"  />
</p>

<p align="center">
Start from visiting S (starting node), and mark it as visited.
<img src="images/BFS2.png"  />
</p>

Get all  unvisited adjacent node from S Choose A, mark it as visited and enqueue it.
<p align="center">
<img src="images/BFS3.png"  />
</p>

The unvisited adjacent node from S is B. Mark it as visited and enqueue it.
<p align="center">
<img src="images/BFS4.png"  />
</p>

The unvisited adjacent node from S is C. We mark it as visited and enqueue it.
<p align="center">
<img src="images/BFS5.png"  />
</p>

S is left with no unvisited adjacent nodes. So, we dequeue and find A.

<p align="center">
<img src="images/BFS6.png"  />
</p>
From A we have D as unvisited adjacent node. We mark it as visited and enqueue it.
<p align="center">
<img src="images/BFS7.png"  />
</p>
<p><b>Breadth First Search: S A B C D</b></p>