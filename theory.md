<h4> Breadth First Search Algorithm</h4>
<p>BFS is a powerful graph traversal technique used to systematically explore all nodes of a graph or tree. It plays a crucial role in various applications, including network routing, shortest path finding</p>

<b>Traversal Technique</b>

<p> BFS explores a graph in a breadth-wise manner. It starts at a specified node (often the root) and systematically visits all nodes at the current level before moving to the next level.</p>
<b>Queue Data Structure</b>
<p>The queue maintains the order in which nodes are visited, ensuring that nodes at the current level are explored before moving to deeper levels.</p>
<b> BFS Algorithm (Step-by-Step)</b>
<ol>
  <li>Initialize a queue and a visited set (or array).</li>
  <li>Enqueue the starting node and mark it as visited.</li>
  <li>While the queue is not empty:
    <ul>
      <li>Dequeue the front node.</li>
      <li>Process it (print/store).</li>
      <li>Enqueue all unvisited neighbors, marking them as visited.</li>
    </ul>
    <li>Repeat until no nodes remain in the queue.</li>
  </li>
</ol>
<h3>Example (Graph Traversal)</h3>

<h4>Graph:</h4>
<pre>
1 -- 2 -- 5
|    |
3 -- 4
</pre>

<p><strong>Start Node:</strong> 1</p>

<h4>Traversal Order (BFS):</h4>
<p>1 → 2 → 3 → 5 → 4</p>

<h4>Explanation:</h4>
<ul>
  <li>Start at 1 → enqueue [1]</li>
  <li>Visit 1, enqueue neighbors [2, 3]</li>
  <li>Visit 2, enqueue [5, 4]</li>
  <li>Visit 3 (already added neighbors)</li>
  <li>Visit 5 → done</li>
  <li>Visit 4 → done</li>
</ul>
<b>Time and Space Complexity</b>
<p>The time complexity of BFS is O(V + E), where V is the number of vertices and E is the number of edges in the graph. The space complexity is also O(V) due to the storage requirements of the queue and visited set.</p>
<b>Properties of BFS:</b>
<li>Shortest Path Finding</li>
<li>Cycle Detection</li>
<li>Level Order Traversal</li>
<li>Bi-directional Search</li>
