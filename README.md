# Scalable Data Mining Algorithms - DaMi (Java-Based)

DaMi is engineered in Java to facilitate scalable data mining algorithms capable of processing vast datasets (up to hundreds of millions of entries) efficiently on PCs with limited memory.

## Key Features and Components

### Utility
- Buffered vectors pool for efficient dataset I/O.
- High-performance, user-friendly text parser. (Further testing in progress)

### Classification
- Implements Stochastic Gradient Descent (SGD) for logistic regression.

### Recommendation Systems
- Features algorithms such as SlopeOne, Singular Value Decomposition (SVD), Randomized SVD (RSVD), and item-neighborhood SVD. (Refer to `movielens_converter.py`)

### Statistical Significance Testing
- Utilizes swap randomization for significance testing.

### Graph Algorithms
- Includes an implementation of the PageRank algorithm.

## Efficiency and Memory Utilization Strategies

1. **Index Utilization**: Employs "id" as an array index for rapid data retrieval.
2. **Memory Management**: Maintains only the model in memory, while data is stored in byte-converted formats for optimized I/O processes.

> **Note**: For optimal performance, it is strongly recommended to use continuous IDs within these algorithms.
