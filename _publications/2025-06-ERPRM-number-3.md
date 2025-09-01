---
title: "Entropy Regularized Process Reward Model"
collection: publications
category: conferences
permalink: /publication/2025-06-ERPRM-number-3
date: 2025-06-15
venue: 'TMLR'
paperurl: 'https://openreview.net/pdf?id=cSxDH7N3x9'
citation: 'Hanning Zhang*, Pengcheng Wang*, Shizhe Diao, Yong Lin, Rui Pan, Hanze Dong, Dylan Zhang, Pavlo Molchanov, & Tong Zhang (2025). Entropy-Regularized Process Reward Model. Transactions on Machine Learning Research.'
---

This paper proposes an Entropy-Regularized Process Reward Model (ER-PRM) to improve mathematical reasoning in large language models. The key novelty is formulating multi-step reasoning under an entropy-regularized Markov Decision Process framework, which balances reward optimization with preventing the policy from deviating too far from its initial distribution. The method derives process reward scores using a novel aggregation approach based on KL-regularized optimization, where rewards are computed as the logarithm of expected exponentiated rewards from completion trajectories sampled by the initial policy. This approach offers theoretical advantages including dual formulation flexibility (soft-max when sampling from initial policy, soft-min from optimal policy) and independence from the optimal policy during reward computation.