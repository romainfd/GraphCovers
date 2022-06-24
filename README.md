# GraphCovers dataset
Code accompanying the paper ["A Topological characterisation of Weisfeiler-Leman equivalence classes"](https://arxiv.org/abs/2206.11876) which will be presented at ICML's workshop Topology, Algebra and Geometry in ML on July 23rd 2022.

In the paper, we give a topological description of all graphs than are indisinguishable using the WL test, and therefore by most message passing Graph Neural Network. We use this description to generate many pairwise non-isomorphic graphs which are indistinguishable by the WL test. Here are a few examples: ![This is an image](https://github.com/jacobbamberger/GraphCovers/blob/main/covers.png)


## Code
In the code we focus on the generationg process, and give an efficient algorithm for testing if two generated graphs are isomorphic. Both are described in Section 3 of the paper. The codebase can be found in [covers.py](https://github.com/jacobbamberger/GraphCovers/blob/main/covers.py), but to get started we recommend checking out the [notebook](https://github.com/jacobbamberger/GraphCovers/blob/main/covers_notebook.ipynb). In the notebook we first generate some graphs, then visualize them, and finally try classifying them with several GNN architecures. Everything can be run on a CPU.
