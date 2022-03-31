# Manifold-aligned Neighbor Embedding

We introduce a neighbor embedding framework for manifold alignment. We demonstrate the efficacy of the framework using a manifold-aligned version of the uniform manifold approximation and projection algorithm. We show that our algorithm can learn an aligned manifold that is visually competitive to embedding of the whole dataset.

![mane embedding](/images/FMNIST_embedding.svg)
Two-dimensional embedding of Fashion-MNIST data. (Left) UMAP embedding of 60,000 points. (Right) Top row: embedding of $D^{(1)}$ and bottom row: embedding of $D^{(2)}$ for the individual UMAP, aligned UMAP, and MANE. Individual UMAPs naturally cannot align the manifolds which can be seen from misalignment of the large cluster consisting of images of ankle boot, sandal and sneaker in the two embeddings. Aligned UMAP and MANE show very good alignment.

![Embedding of Shared Points](/images/D0D0_FMNIST.svg)
Shared data points from the two-dimensional embedding of the Fashion-MNIST dataset of the figure above. (Left) Individual UMAPs of sets $D^{(1)}$ and $D^{(2)}$ show that the shared information is not aligned between two datasets. (Middle) Aligned UMAP shows close alignment between the shared points. (Right) MANE shows best alignment between the shared points.

