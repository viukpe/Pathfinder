# Pathfinder

## Description

Pathfinder is simple visualization tool that shows the working of the A* path finding algorithm

## How to run

Simply fork into your repo and run pathfinder.py in an IDE

Selecting start node : The first cell you select is your start node (right click to undo)

Selecting end node : The second cell you select is your end node (right click to undo)

To draw barrier : Simply click on any cell and drag to construct a barrier (Do this as many times as you like, right click to undo)

To run visualizer : Simply click on your space bar

## Further description

The A* algorithm is a further improvement on the famous Djikstra's algorihm, it improves on Djikstra's by the use of a more informed search,  it chooses what nodes to traverse next based on the total cost of visiting a new node using the formula f(v) = h(v) + g(v)

Where h(v) is the distance between the current node and the end node.
      g(v) is the distance between the current node and the start node.

The distance metric used for this implementation is manhattan distance (diagonal distance is not accounted for).