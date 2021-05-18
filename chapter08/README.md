## Graphical models

- A graph G=(V,E) comprises nodes (also called vertices, V) connected by links (also known as edges, E or arcs).

- In a **probabilistic graphical model**, each node represents a random variable (or group of random variables), and the links express probabilistic relation- ships between these variables.

- The graph captures the way in which the joint distribution over all of the random variables can be decomposed into a product of factors each depending only on a subset of the variables.

- There are two major classes of **graphical models**:

- **Bayesian networks**, also known as _directed_ graphical models, in which the links of the graphs have a particular directionality indicated by arrows.

- **Markov random fields**, also known as _undirected_ graphical models, in which the links do not carry arrows and have no directional significance.

- Directed graphs are useful for expressing causal relationships between random variables

- Undirected graphs are better suited to expressing soft constraints between random variables.

- For solving inference problems, it is often convenient to convert both directed and undirected graphs into a different representation called a **factor graph**.


## Markov Random Fields


- See Markov Random Field For Image Segmentation and Denoising (https://github.com/AliMorty/Markov-Random-Field-Project/blob/master/Codes/Complete_version.ipynb)
