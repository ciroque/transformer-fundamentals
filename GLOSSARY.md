# Glossary

## PCA

**Principal Component Analysis (PCA)** is a dimensionality reduction technique used in machine learning and statistics.

**Purpose**: Reduces high-dimensional data to fewer dimensions while preserving as much variance (information) as possible.

**How it works**: Finds orthogonal axes (principal components) that capture the maximum variance in the data.

**Use cases**:
- Visualizing high-dimensional embeddings (e.g., reducing 512-dim vectors to 2D for plotting)
- Reducing computational complexity
- Removing noise and redundant features
- Data compression

**In the context of transformers/embeddings**: PCA is commonly used to visualize word embeddings by projecting them from their original high-dimensional space (e.g., 768 dimensions in BERT) down to 2 or 3 dimensions that can be plotted on a graph. This helps understand relationships between tokens visually.
