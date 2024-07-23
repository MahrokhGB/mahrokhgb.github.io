---
title: "Personalized Federated Learning of Probabilistic Models: A PAC-Bayesian Approach
" 
date: 2024-01-16
lastmod: 2024-01-16
tags: ["PAC-Bayes","Federated Learning","Probabilistic Models"]
author: ["Mahrokh Ghoddousi Boroujeni", "Andreas Krause", "Giancarlo Ferrari-Trecate"]
description: "This paper introduces PAC-PFL, a personalized federated learning algorithm that leverages PAC-Bayesian theory and differential privacy to enhance model accuracy and calibration for heterogeneous clients, validated through experiments on various datasets. Under review." 
summary: "This paper proposes PAC-PFL, a personalized federated learning algorithm using a PAC-Bayesian framework and differential privacy to enhance model accuracy and calibration for heterogeneous clients, demonstrated through experiments on multiple datasets." 
cover:
    image: "35_setup.pdf"
    alt: "Setup"
    relative: false
editPost:
    URL: "https://github.com/MahrokhGB/Federated-Hyper-Posterior-Learning"
    Text: "Under review"

---

---

##### Download

+ [Paper](PAC_PFL_TMLR.pdf)
+ [Code](https://github.com/MahrokhGB/Federated-Hyper-Posterior-Learning)

---

##### Abstract

Federated learning aims to infer a shared model from private and decentralized data stored locally by multiple clients. Personalized federated learning (PFL) goes one step further by adapting the global model to each client, enhancing the model's fit for different clients. A significant level of personalization is required for highly heterogeneous clients, but can be challenging to achieve especially when they have small datasets. To address this problem, we propose a PFL algorithm named PAC-PFL for learning probabilistic models within a PAC-Bayesian framework that utilizes differential privacy to handle data-dependent priors. Our algorithm collaboratively learns a shared hyper-posterior and regards each client's posterior inference as the personalization step. By establishing and minimizing a generalization bound on the average true risk of clients, PAC-PFL effectively combats over-fitting. PACPFL achieves accurate and well-calibrated predictions, supported by experiments on a dataset of photovoltaic panel power generation, FEMNIST dataset, and Dirichlet-partitioned EMNIST dataset.

---

##### Fig 1: Setup

![](35_setup.pdf)

---

##### Citation

M.G.Boroujeni,A.Krause,andG.Ferrari-Trecate,“Personalizedfed- erated learning of probabilistic models: A PAC-Bayesian approach,” arXiv preprint arXiv:2401.08351, 2024.

```BibTeX
@misc{boroujeni2024personalizedfederatedlearningprobabilistic,
      title={Personalized Federated Learning of Probabilistic Models: A PAC-Bayesian Approach}, 
      author={Mahrokh Ghoddousi Boroujeni and Andreas Krause and Giancarlo Ferrari Trecate},
      year={2024},
      eprint={2401.08351},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2401.08351}, 
}
```

---

