# M&TBank RM Workbench

These are graphs that were custom-made for M&T bank using SVG in javascript.
The reason they had to be custom instead of using a library is because of the design of the graph.
The client required the botton of each graph to be flat instead of sloped.
This demanded a custom grapgh drawing library that drew the graph in several arches as opposed to a circle.

The data was retrieved via REST.
There we also multiple views depending on the user, if they wanted more data, or if they were trying to print.
The More data view brought up a modal, where it displayed all the user's data.
