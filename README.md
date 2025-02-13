# Attention Mechanisms

This repository provides minimalistic implementations of various attention mechanisms commonly used in deep learning models, including:

- **Multi-Head Attention**
- **Multi-Query Attention**
- **Grouped-Query Attention**
- **Multi-Head Latent Attention**

## Implemented Classes

### 1. Multi-Head Attention

The `MultiHeadAttention` class implements the standard multi-head attention mechanism, which allows the model to jointly attend to information from different representation subspaces.

### 2. Multi-Query Attention

The `MultiQueryAttention` class implements the multi-query attention mechanism, where multiple query heads share a single set of key and value heads. This approach reduces memory usage and computational complexity.

### 3. Grouped-Query Attention

The `GroupQueryAttention` class implements the grouped-query attention mechanism, which strikes a balance between multi-head and multi-query attention by grouping query heads and sharing key-value pairs within each group.

### 4. Multi-Head Latent Attention

The `MultiHeadLatentAttention` class implements a variant of multi-head attention that projects inputs into a latent space for key and value computations, potentially reducing dimensionality and computational load.

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/attention-mechanisms.git
cd attention-mechanisms
pip install -r requirements.txt
```

For detailed explanations and theoretical backgrounds, please refer to the origin paper references given along with code in notebook.

