<h6 align="center"> LauzHack - EPFL</h6>

<h1 align="center">UBS Efficient Entity Resolution: Clustering and Embedding-Based Matching</h1>


<div style="text-align: justify;">
This project focuses on resolving external counterparties efficiently by combining clustering, embeddings, and similarity-based classification. Instead of comparing all entities exhaustively, we use clustering and embedding-based techniques to narrow down potential matches, significantly improving computational efficiency and scalability.
</div>

###### Team Members
- Daniela Álvarez
- Elena Alegret
- Jofre Moseguí
- Andrea Quiroz

###### The Challenge
Comparing 1.4 million entities directly is computationally prohibitive, leading to billions of pairwise comparisons. Our approach minimizes this complexity by:
1. Pre-clustering entities into ~1400 groups using K-Means.
2. Embedding new entries to find their nearest cluster centroid.
3. Resolving entities within clusters based on similarity measures.








