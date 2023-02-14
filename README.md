# HERACLES
HERACLES algorithm reconstructs CRISPR-Cas9 lineages with hyperbolic embeddings

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Insert CRISPR-Cas9 casettes (i.e. cellular "barcodes") into a cell and sequence its descendants to reconstruct the evolutionary cell lineage. Using a CRISPR-specific continous time Markov chain, model the mutations that accumulate on these casettes. Then construct a function to quanitify the likelihood of a particular evolutionary tree, in both tree topology and branch lengths. Approixmate the tree-metric by embedding points in hyperbolic space. Lastly, optimize over the hyperbolic embeddings using Riemannian stochastic gradient descent.
