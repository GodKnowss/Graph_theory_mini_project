# Graph theory mini project
## Florida Pathfinding Algorithms Visualization
### Project Overview
This interactive visualization tool demonstrates various pathfinding algorithms in a graph of major Florida cities. It was developed to enhance understanding of graph traversal and pathfinding algorithms by providing clear visual comparisons between:
* Breadth-First Search (BFS)
* Dijkstra's Algorithm
* A* Search Algorithm
### Features
* Interactive Map Visualization: A network representation of Florida cities with accurate distances
* Algorithm Selection: Switch between BFS, Dijkstra's, and A* algorithms with immediate visual feedback
* Customizable Parameters: Select start/end cities, adjust animation speed, and toggle exploration order display
* Real-time Statistics: View performance metrics, including path distance, cities explored, and execution time
* Color-Coded Elements: Easily distinguish between start points, destinations, explored nodes, and final paths
### Educational Value
This project improves upon typical algorithm visualizations by:
1. Contextualizing abstract concepts in a real-world geographic setting
2. Highlighting the trade-offs between different pathfinding approaches:
    * BFS finds paths with the fewest cities/connections
    * Dijkstra finds paths with the shortest total distance
    * A* uses heuristics to efficiently find the shortest paths
3. Providing clear visual feedback about how each algorithm makes exploration decisions
### Implementation Details
* Built using Python with NetworkX for graph operations and Matplotlib for visualization
* Leverages Jupyter widgets for interactive controls
### How to Use
1. Run the notebook in a Jupyter environment
2. Call the create_reliable_visualizer() function to launch the interactive interface
3. Select your desired algorithm, start city, and destination city
4. Toggle "Show exploration order" to see the sequence of city explorations
5. Observe the differences in exploration patterns and final paths between algorithms
### Requirements
* Python 3.6+
* NetworkX
* Matplotlib
* ipywidgets
* Jupyter Notebook or JupyterLab
## Future Improvements
* Add more pathfinding algorithms 
* Create animations to show the step-by-step progression of each algorithm
