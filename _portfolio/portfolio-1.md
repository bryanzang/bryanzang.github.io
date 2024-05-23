---
title: "Graphify"
excerpt: "Given an image of a graph, the program will return certain characteristics such as whether the graph is bipartite or whether the graph is a forest"
collection: portfolio
---

Link to project [`here`](https://github.com/bryanzang/Graphify)

Using the definitions from the University of Waterloo's MATH239 (intro to Combinatorics) course, this program attempts to detect a given image of a graph and output corresponding properties. `OpenCV` and `matplotlib` are used for the image processing (both detection and redrawing) and `networkx` is used for most of the graphical computations. Testing was mostly done with graphs created [`here`](https://csacademy.com/app/graph_editor/); although there are graphs taken from the MATH239 course notes.
