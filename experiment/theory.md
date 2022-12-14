### Breadth First Search Algorithm

##### Starts at some an arbitrary node of a graph and explores the neighbour node first before moving to the next level neighbours.Used for graphs without loop.All edges have same weight or no weight.

<ol>
<li> Take an Empty Queue.</li>
<li> Select a starting node (visiting a node) and insert (enqueue) it into the Queue.</li>
<li>Provided that the Queue is not empty, extract the node from the Queue and insert its child nodes  into the Queue.</li>
<li>Add extracted node to the path </li>
</ol>  

##### Example
<ul>
<li> Select  ‘A’ as the root node and insert it into the Queue.</li>
<li> Extract node ‘A’ from the queue and insert the child nodes of ‘A’, i.e., ‘B’ and ‘C’.</li>
<li> Add tp the path node ‘A’.</li>
<li> The queue is not empty and has node ‘B’ and ‘C’. Since ‘B’ is the first node in the queue, let’s extract it and insert the child nodes of ‘B’, i.e., node ‘D’ and ‘E’. </li>
<li> Repeat these steps until the queue gets empty. Note that the nodes that are already visited should not be added to the queue again.</li>
</ul>

## Example 

![BFS1]
<p align="center">
<img src="images/BFS1.png"  />
</p>
ENQUEUED the first element

![BFS2]
<p align="center">
<img src="images/BFS2.png"  />
</p>
DEQUEUED the first element 


![BFS3]
<p align="center">
<img src="images/BFS3.png"  />
</p>
ENQUEUED the second element

![BFS4]
<p align="center">
<img src="images/BFS4.png"  />
</p>
ENQUEUED the third element


![BFS5]
<p align="center">
<img src="images/BFS5.png"  />
</p>
DEQUEUED the second element

![BFS6]
<p align="center">
<img src="images/BFS6.png"  />
</p>
DEQUEUED the third element