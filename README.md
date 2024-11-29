# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


///

By the def of isomorphism, only the correspondence between vertices and edges is required to be the same, the graph does not need to be fully connected, and connectivity is not a necessary condition for isomorphism.

For example

G1 = (v1 = {a,b}, E1 = ∅)

G2 = (v2 = {x,y}, E2 = ∅)

Define f(a) = x, f(b) = y

E1 and E2 are consistent, G1 and G2 are isomorphic but not completely connected

###

source：https://en.wikipedia.org/wiki/Isomorphism https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#what-is-graph-isomorphism https://en.wikipedia.org/wiki/Bijection

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
