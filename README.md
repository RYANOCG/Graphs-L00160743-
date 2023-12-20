# Graphs-L00160743-

ReadMe for Graphs Assignment for module Advanced algortithms and dat structures.

Reads out shortest path for the first graph(g)
In the GraphTester class it's set to read out all nodes in order with all shortest paths to relevant nodes along with cost of each path in dijkstra (g2)

In the GraphMenu class when you click run it prints out a menu with 6 choices consisting of 1.Create a new graph, 2.Add node, 3.Connect nodes, 4.Algorithm menu, 5.Load Pre-built Menu and finally 0.Exit.

Before a user can add a node they have to create a new graph, it will print this message if the user tries to create a node prior to creating a graph. This will also occur with the connect nodes option along with a message if the graph is created but no nodes have been created or are invalid.

when the user tries to connect two nodes it will give them the option whether they want them to be directional or undirectional.

when the user enters option 4 it will print out a menu of 4 choices which are 1. Breadth-First Search (BFS), 2. Shortest Path, 3. Dijkstra's Algorithm, 0. Back to Main Menu. if any of these are attempted without a prior graph and nodes created an error will occur.
when option 3 is selected for dijkstras algorithm it will ask "Enter the label for the end node (or press Enter for a full traversal)" the output will still result in a full traversal even if the user only enters a single node.
option 0 will exit the algorithm menu and then print out the graph menu.

option 5 will use the graph that is in the code. the user can use this if they don't want to have to create a graph and all processes can be done through it.

option 0 will exit the program and say goodbye.
