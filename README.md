[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12590774&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer

Assuming that two graphs $A$ and $B$ do not have the same number of nodes. To be isomorphism about every two graphs, it means that need exist a one-to-one and onto mapping between them. 

A function f: A-->B is said to be one-to-one if each node in graph A maps to a distinct node in map to the same element in B. But, for the different number of nodes of two graph, because one node in A mapping to B may be exist several nodes match or haven't match any node in B, which is obviously violate one-to-one when different number of nodes between the graph A and the graph B.

A function f saied onto is if any node in the graph B has at least one edge mapping to some vetex in graph A. Since two graphs $A$ and $B$ do not have the same number of nodes, they can't be isomorphic.


