# Undirected graph planarity check "The Left-Right Planarity Test" implementation on Python 3

The article states that the graph is planar if and only if it has LR-partition. In the class PlanarityChecker (from planaritychecker.py) is\_planar method checks that.

The algorithm works in O(|V|) = O(|E|)(in planar graphs |E| <= 3*|V|+6)

Graph planarity checking is used in the automated design of printed circuit boards, in Biology for big molecules drawing, as a part of maximal-planarization algorithms etc.

Example of checker working you can found in "Planarity check example.ipynb" (requires networkx and planarity libraries).

Based On: "The Left-Right Planarity Test" (Ulrik Brandes, 2009), http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.217.9208
