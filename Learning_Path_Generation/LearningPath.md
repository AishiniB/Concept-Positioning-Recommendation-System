This folder contains attempts to devise a learning path from one concept to another, making use of knowledge graphs.

Approaches employed:
1. **Textbook Mining**: BERT was fine-tuned on comprehensive data science and algorithm books. I found out semantic similarities between tags based on the books and formed a knowledge graph.
2. **Hierarchy assigning**: I queried GPT to rate relative difficulty of concepts which had an edge between them. Then I used the AHP algorithm to assign absolute hierarchical scores to concepts.
