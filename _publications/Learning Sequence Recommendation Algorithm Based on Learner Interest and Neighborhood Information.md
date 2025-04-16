---
title: "Learning Sequence Recommendation Algorithm Based on Learner Interest and Neighborhood Information"
collection: publications
permalink: "/publication/learning-sequence-recommendation-algorithm"
excerpt: |
  Now, most of the sequential recommendation algorithms model learner interests and course information based on the current learner's learning sequence, lacking the use of course order information and mining course information in the neighborhood sequence, which makes it difficult to capture accurate learner interests and comprehensively describe course information. In response to the above issues, this paper fully uses the sequential recommendation method and proposes an online course Recommendation Algorithm Based on Learner Interests and Neighborhood Information (LINI-CR). The algorithm learns the contextual relationships of courses in an interaction sequence through a GRU (Gate Recurrent Unit) and superimposes the learning sequence information to model learner interests. Then, it searches for similar sequences based on the interaction sequences of learners and courses, constructs a neighborhood course sequence graph using the set of similar sequences, and uses directed graph attention propagation on the structure of this graph to mine the higher-order connectivity information of courses. On this basis, the probability of learner-course interaction is obtained through inner product operation and normalization, and course recommendation is based on the probability. Experiments were conducted on the MOOCCourse and MovieLens-1M datasets, and the results proved the accuracy and effectiveness of the algorithm, with an improvement in each evaluation metric compared to the better-performing baseline method, Precision@20 improves by 3.97%, 2.12% and NDCG@20 improves by 5.23%, 1.03%, respectively.
date: 2024-10-18
venue: "5th International Conference on Computer Science and Management Technology (ICCSMT)"
paperurl: "https://doi.org/10.1145/3708036.3708124"
citation: 'L. Wang, L. Feng, H. Wu, L. Zhang, T. Cheng, "Learning Sequence Recommendation Algorithm Based on Learner Interest and Neighborhood Information," <i>Proc. ICCSMT 2024</i>, pp. 513-519. doi:10.1145/3708036.3708124'
---

### Contribution

<div style="text-align: justify;">
Based on the above problems and background, this paper has done related research work, which mainly includes: <br>
  1. proposing a learning sequential recommendation algorithm based on the learner's interests and neighborhood courses, which combines the learner's interests with similar course sequences for a predictive recommendation of future courses; <br>
  2. in the algorithm, the information enhancement of the target course by using the neighborhood courses through the directed graph attention propagation layer effectively improves the expression of the target course; <br>
  3. The effectiveness and accuracy of the algorithm proposed in this paper are demonstrated by comparison tests and ablation experiments on two datasets, MOOCCourse and MovieLens-1M.
</div>




