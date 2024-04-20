[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If graph $A$ and graph $B$ are completely connected and have the same amount of nodes, we could look at an example like this:\
To have the same amount of nodes, graphs must look like this: graph $A = (1, 2, 3)$ and graph $B = (a, b, c)$.\
The 2 graphs can have any number of nodes, but following the guidelines of the proof, they must have the same number of nodes.\
For the graph's to be completely connected they must have edges for $A$ be $(1, 2), (2, 3), (3, 1)$ and for $B$ be $(a, b), (b, c), (c, a)$, where all nodes are connected to eachother.\
If we have a bijection $f: V_1 \rightarrow V_2$, then we can map all of the nodes in graph $A$ to the nodes in graph $B$.\
$f(1) = a, f(2) = b, f(3) = c$.\
Similarly, we can map all of the edges in graph $A$ to the edges in graph $B$.\
$f(1,2) = (a, b), f(2, 3) = (b, c), f(3, 1) = (c, a)$.\ 
Because of the bijection for edges and nodes in graphs $A$ and $B$, these graphs are by definition isomorphic. 
For all graphs following the rules of having the same number of nodes and being completely connected, there must be an equal number of nodes in each graph.\
There must also be an equal number of edges in each graph, where every possible edge exists. For a node in one graph to be mapped to a node in the other graph,\
both nodes must have the same number of edges connected to them. This is called the degree. So in 2 graphs that are completely connected,\
then every node could be mapped to any one node in the other graph, because all of the nodes have the same degree. This proves that 2 graphs that have the same\
number of nodes and are completely connected will always be isomorphic.
