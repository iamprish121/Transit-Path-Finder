# Transit-Path-Finder

Please don't get confused, this is NOT an ANDROID Application!

This is a simple Java program that will take information (name) of the source station and the destination station, of Delhi Metro, from the user and display the fare and shortest metro route to reach the destination. It will also be having a metro map for commuter’s better navigation.

The idea is implemented using Graph and Heap data structures.
The graph has nodes and edges. Nodes represent a metro station that will be containing certain information regarding that station like its name, its metro corridor, and the lines which it connects. Edges (the connection between two nodes) represent the distance between the two stations and the cost of each edge will be equal to the distance between the two of its connecting stations(nodes). 

By using different algorithms like Dijkstra, breadth-first search, depth-first search, etc, the shortest path between the source station and the destination station is determined, and accordingly, the fare is being calculated on the basis of the total distance between the two stations. Finally, the metro route between the two stations and the total fare is displayed.

Main.java cointains all the major code and Heap.java contains heap implementation.


##  REQUIREMENTS

> The project can run on any online or offline Integrated Development Environment (IDE) like Eclipse, Netbeans, ideone.com, etc.
> You should have at least elementary knowledge of Java Programming language to work on the project.
> Knowledge of data structures like Graph and Heap and Algorithms like Dijkstra, BFS, DFS, etc is appreciated, however, it is not essential.
> And lastly, some understanding of the Collection framework makes it a cakewalk journey. 
## Collection framework used in this project

### In Graph_M.java

*  ArrayList
* LinkedList
* Stack
* HashMap

### In Heap.java

* HashMap
* ArrayList



## Data Structures
Data structure is a way of organizing data in the computer so that it can be used effectively.
The data structures used in this project are:
* Array
* HashMap
* Linked List
* Heap
* Stack
* Graph

* The array data structure is implemented using ArrayList class which is a resizable array.It stores data in contiguous memory locations.
* Hashmap data structure is used to store key-value pairs.
* The stack data structure required by the algorithm is implemented using linked list.It follows the principle Last In First Out(LIFO)
* Heap is implemented with the help of ArrayList and HashMap.It is a tree based data structure where all elements of the tree are in a particular order.
* Graph is a complex data structure containing vertices and edges connecting these vertices.This is implemented in the project with the help of ArrayList and HashMap.
