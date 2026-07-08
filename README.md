# LFBC : Logarithmic Fusion of Binary Classifiers
Data annotation technique.

Heterogeneity in real-world collaborative learning environments that extends beyond data distributions. Participating silos often deploy different model architectures due to computational constraints, legacy systems, or application-specific requirements. 
In addition, clients may observe only partial subsets of the global label space, and the coordinating server may lack labeled data altogether.
Under such conditions, parameter-level aggregation—central to most FL frameworks—becomes infeasible or ineffective. Furthermore, conventional FL frameworks typically treat the server as a passive aggregation entity, ignoring the presence of unlabeled data at the server, such as publicly available samples or continuously acquired data streams. 
This represents a missed opportunity for improving global learning.
These constraints motivate heterogeneity-aware learning frameworks that operate at the level of predictions rather than parameters and treat the server as an active learner.
Leveraging pooled client predictions to generate pseudo-labels for unlabeled server-side data offers a principled mechanism to consolidate knowledge across heterogeneous clients without requiring architectural or label homogeneity.
