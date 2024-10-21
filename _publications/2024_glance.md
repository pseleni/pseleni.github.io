---
title: "GLANCE: Global Actions in a Nutshell for Counterfactual Explainability"
collection: publications
category: preprints
# permalink: /publication/glance
excerpt: 'with Loukas Kavouras, Konstantinos Tsopelas, Dimitrios Rontogiannis, Nikolaos Theologitis, Dimitris Sacharidis, Giorgos Giannopoulos, Dimitrios Tomaras, Kleopatra Markou, Dimitrios Gunopulos, Dimitris Fotakis and Ioannis Emiris'
date: 2024-05-29
venue: 'arXiv 2024 (Under Submission)'
paperurl: 'https://arxiv.org/pdf/2405.18921'
citation: 'Kavouras, L., Psaroudaki, E., Tsopelas, K., Rontogiannis, D., Theologitis, N., Sacharidis, D., Giannopoulos, G., Tomaras, D., Markou, K., Gunopulos, D., Fotakis, D., and Emiris, I., 2024. GLANCE: Global Actions in a Nutshell for Counterfactual Explainability. arXiv preprint arXiv:2405.18921.'
bib: './../files/glance.bib'

---

The widespread deployment of machine learning systems in critical real-world decision-making applications has highlighted the urgent need for counterfactual explainability methods that operate effectively. Global counterfactual explanations, expressed as actions to offer recourse, aim to provide succinct explanations and insights applicable to large population subgroups. Effectiveness is measured by the fraction of the population that is provided recourse, ensuring that the actions benefit as many individuals as possible. Keeping the cost of actions low ensures the proposed recourse actions remain practical and actionable. Limiting the number of actions that provide global counterfactuals is essential to maximize interpretability. The primary challenge, therefore, is balancing these trade-offs, i.e., maximizing effectiveness, minimizing cost, while maintaining a small number of actions. We introduce GLANCE, a versatile and adaptive framework, comprising two algorithms, that allows the careful balancing of the trade-offs among the three key objectives, with the size objective functioning as a tunable parameter to keep the actions few and easy to interpret. C-GLANCE employs a clustering approach that considers both the feature space and the space of counterfactual actions, thereby accounting for the distribution of points in a way that aligns with the structure of the model. T-GLANCE provides additional features to enhance flexibility. It employs a tree-based approach, that allows users to specify split features, to build a decision tree with a single counterfactual action at each node that can be used as a subgroup policy. Our extensive experimental evaluation demonstrates that our method consistently shows greater robustness and performance compared to existing methods across various datasets and models.