Download Link: https://assignmentchef.com/product/solved-big-homework-3-data-structures-and-algorithms-bst-heaps
<br>
<strong> </strong><strong>1)</strong><strong> BST (5p) </strong>

<ol>

 <li>Read letters from the keyboard and insert them in a BST. The reading process stops when the user inserts the character 0 (zero) (0.5p)</li>

 <li>Find the common ancestor of 2 given nodes (0.75p)</li>

 <li>Write a function to check is a node is a grand-parent of a given node. (0.75p)</li>

 <li>Design an algorithm which creates a linked list of all the nodes at each depth (i.e., if the tree has depth D, you’ll have D linked lists). (1p)</li>

 <li>Check if a BST is perfect or not (all leaves are at the same distance from the root and all internal nodes have 2 children) (1p)</li>

 <li>Perform a right rotation of the BST. (1p)</li>

</ol>

More info: <a href="https://slideplayer.com/slide/14553828/">https://slideplayer.com/slide/14553828/</a> Ex:




<strong>2)</strong><strong> Heap (5p) </strong>

A tournament tree is a form of max (min) heap which is a complete binary tree. Every external node (leaf) represents a player and an internal node represents a winner. We will thus have N-1 internal nodes in a binary tree with N leaves.  Ex:




The above (max) tree contains 4 leaf nodes that represent players (5, 3, 7, and 8). We have 3 levels: 0, 1 and 2. Initially 2 games are played at level 2, one between 5 and 3 and another one between 7 and 8. In the next move (level 1), one more game is conducted between 5 and 8 to conclude the final winner. Overall we need 3 comparisons to find the winner.




<ol>

 <li>Check if an input set can form a tournament tree after being inserted in a heap and display an appropriate message. (1p)</li>

</ol>

Ex: 3, 5, 5, 6, 6, 2, 5 – it can form a tournament tree 3, 5, 5, 6, 2 – it cannot form a tournament tree

Pick a valid set and insert it in your tournament tree.

<ol>

 <li>Determinate who is the “second best” player. This is the person who lost in the first round the match against the final winner (here the second best is: 7) (0.5p) c) Display the history of the matches played by the winner at each level. (1p) Ex:</li>

</ol>

In the first round, the winner defeated 7.

In the second round, the winner defeated 5 etc.

<ol>

 <li>Construct a “loser tree” using the previous info from the tournament tree (2p). Ex:</li>

</ol>




In round 1, between 5 and 3, 3 is the loser; between 7 and 8, 7 is the loser. In round 2, we             have the match between the 2 previous winners (5 and 8): the loser is 5. The winner is 8!

<ol>

 <li>Determinate the winner and the main loser from the loser tree (0.5p).</li>

</ol>