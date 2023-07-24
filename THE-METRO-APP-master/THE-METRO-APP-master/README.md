# DELHI METRO RAIL APP

This is a Java project which will take information (name) of the source and destination of station of Delhi Metro which will be inputted from the user, and the output will be displayed as the fare and shortest metro route to reach the destination. It will also be having a metro map for commuter's better navigation.

The data structures involved in this are Graph and Heap data structures, the graph(in this case is the whole metro route) has nodes and edges. Nodes represent a metro station that will be containing data about the station ie. name, metro corridor and the lineways its connecting. Edges(the connection between two nodes) represent the distance between the two stations and the cost of each edge will be the distance bewteen the two of its connecting stations(nodes).

Determination of shortest path between the source station and the destination is determined using well known graph algorithms like Dijkstra(single sourced shortest distance), BFS and DFS, and accordingly the fare is calculated. Finally, the metro route bewteen the two stations and the total fare is displayed.

Main.java contains all the major code and Heap.java contains heap implementation.
	


