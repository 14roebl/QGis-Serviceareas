# QGis-Serviceareas
QGis Programm for creating service areas with various algorithms.
Development with Python 2.17 in QGis 2.18.17


This project supports the calculation of service areas based on streetnetworks with different Shortest-Path-Algorithms. 

The following Algorithms can be used:
  - Naive Dijkstra
  - Simple Implementation of Dijkstra with Buckets
  - Two_Q (Graph Growth algorithm of Pallotino with two Queues)
  - SBB (Streetbased Buffer) - Development of Buffer method


The file main.py is the main Programm, where the graph is build out of the given streetnetwork and the Service Area is created
For parameters you can give impedance of the service area in meters, algorithm and number of firestation/s of which you want to create service area

A few test cases are given at the end of main.py

For further information and explaination regarding algorithms and implementation details conntact david.roebl@yahoo.com or just ask here.
