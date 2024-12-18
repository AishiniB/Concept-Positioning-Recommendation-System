This folder contains all approaches undertaken to make an effective recommender.

1. **Neural Collaborative Filtering**: This method makes use of matrix factorization and multi-layer perceptrons to capture user-tag interactions.
   The following paper has been used as reference: *https://dl.acm.org/doi/10.1145/3038912.3052569*
   Sample recommendations have been stored in the files: *strictly_more_difficult.csv*, *not_so_strict.csv*, *average.csv*. Three kinds of thresholds were used in making these recommendations, making use of the same method.

2. **Cold Start Recommendation**: For facilitating recommendations for cold start problems, LLM augmentation is used to generate pairwise preferences, providing better training signals. The following paper has been used as reference: *https://arxiv.org/pdf/2402.11724* (Possible Future Extension)

3. **Restricted Botlzmann Machine**: Reference paper: *https://dl.acm.org/doi/pdf/10.1145/1273496.1273596*
