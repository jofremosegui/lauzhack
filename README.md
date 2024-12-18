<h6 align="center"> LauzHack - EPFL</h6>

<h1 align="center">UBS Efficient Entity Resolution: Clustering and Embedding-Based Matching</h1>

<h6 align="center">
Daniela Álvarez, Elena Alegret, Jofre Moseguí, Andrea Quiroz
</h6>

<div style="text-align: justify;">
This project focuses on resolving external counterparties efficiently by combining clustering, embeddings, and similarity-based classification. Instead of comparing all entities exhaustively, we use clustering and embedding-based techniques to narrow down potential matches, significantly improving computational efficiency and scalability.
</div>

###### The Challenge
Comparing 1.4 million entities directly is computationally prohibitive, leading to billions of pairwise comparisons. Our approach minimizes this complexity by:
1. Pre-clustering entities into ~1400 groups using K-Means.
2. Embedding new entries to find their nearest cluster centroid.
3. Resolving entities within clusters based on similarity measures.

#### Workflow overview

<p align="center">
    <img width="550" alt="Screenshot 2024-12-01 at 12 00 05" src="https://github.com/user-attachments/assets/cde4b524-aee1-49ff-8bea-742b4dc2d4af">
    <img width="450" alt="Screenshot 2024-12-01 at 12 00 32" src="https://github.com/user-attachments/assets/d09b16d5-c4b9-4c93-b984-dbabd7c37977">

</p>

<p align="center">
    <em>Figure 1: K-Means Structure Overview </em>  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
    <span style="margin-left: 110px;"> <em>Figure 2: New Entry Structure Overview</em> </span>

</p>
