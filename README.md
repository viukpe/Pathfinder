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

## Visuals

<img width="799" alt="Screen Shot 2023-01-13 at 5 52 29 PM" src="https://user-images.githubusercontent.com/72221782/212422390-2698b1dd-0933-463a-852c-b86bf73b0c34.png">

<img width="798" alt="Screen Shot 2023-01-13 at 5 53 17 PM" src="https://user-images.githubusercontent.com/72221782/212422626-d6e19dc8-91e5-4190-bdbd-a0498d9288e0.png">

<img width="800" alt="Screen Shot 2023-01-13 at 5 54 27 PM" src="https://user-images.githubusercontent.com/72221782/212422699-1cb417f0-b7ac-4728-ad19-91ba11096ed6.png">

<img width="800" alt="Screen Shot 2023-01-13 at 5 54 54 PM" src="https://user-images.githubusercontent.com/72221782/212422774-41c55b3d-beb3-4708-bca6-9f1bf9688930.png">
