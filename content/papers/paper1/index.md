---
title: "A PAC-Bayesian Framework for Optimal Control with Stability Guarantees" 
date: 2024-03-26
lastmod: 2024-03-26
tags: ["PAC-Bayes","Policy Learning","Stability"]
author: ["Mahrokh Ghoddousi Boroujeni", "Clara Lucía Galimberti", "Andreas Krause", "Giancarlo Ferrari-Trecate"]
description: "This paper presents a novel approach using PAC-Bayes theory to provide generalization bounds for Stochastic Nonlinear Optimal Control (SNOC), enhancing control policy reliability and mitigating overfitting, demonstrated through neural network controllers in cooperative robotics. To appear in the IEEE Conference on Decision and Control, 2024." 
summary: "The paper introduces a novel method leveraging PAC-Bayes theory to establish rigorous generalization bounds for Stochastic Nonlinear Optimal Control (SNOC), aiming to improve control policy reliability and mitigate overfitting. The approach incorporates prior knowledge into the synthesis process and ensures closed-loop stability, demonstrated through the design of neural network controllers for cooperative robotics tasks." 
cover:
    image: "svgd.gif"
    alt: "Our controller"
    relative: false
editPost:
    URL: "https://github.com/DecodEPFL/PAC-SNOC"
    Text: "IEEE Conference on Decision and Control"

---

---

##### Download

+ [Paper](PAC-SNOC_CDC.pdf)
+ [Code](https://github.com/DecodEPFL/PAC-SNOC)

---

##### Abstract

Stochastic Nonlinear Optimal Control (SNOC) involves minimizing a cost function that averages out the random uncertainties affecting the dynamics of nonlinear systems. For tractability reasons, this problem is typically addressed by minimizing an empirical cost, which represents the average cost across a finite dataset of sampled disturbances. However, this approach raises the challenge of quantifying the control performance against out-of-sample uncertainties. Particularly, in scenarios where the training dataset is small, SNOC policies are prone to overfitting, resulting in significant discrepancies between the empirical cost and the true cost, i.e., the average SNOC cost incurred during control deployment. Therefore, establishing generalization bounds on the true cost is crucial for ensuring reliability in real-world applications. In this paper, we introduce a novel approach that leverages PAC-Bayes theory to provide rigorous generalization bounds for SNOC. Based on these bounds, we propose a new method for designing optimal controllers, offering a principled way to incorporate prior knowledge into the synthesis process, which aids in improving the control policy and mitigating overfitting. Furthermore, by leveraging recent parametrizations of stabilizing controllers for nonlinear systems, our framework inherently ensures closed-loop stability. The effectiveness of our proposed method in incorporating prior knowledge and combating overfitting is shown by designing neural network controllers for tasks in cooperative robotics.

---

##### Gif: Our Controller

![](svgd.gif)

---

##### Citation

M. G. Boroujeni, C. L. Galimberti, A. Krause, and G. Ferrari-Trecate, “A
pac-bayesian framework for optimal control with stability guarantees,”
arXiv preprint arXiv:2403.17790, 2024.

```BibTeX
@misc{boroujeni2024pacbayesianframeworkoptimalcontrol,
      title={A PAC-Bayesian Framework for Optimal Control with Stability Guarantees}, 
      author={Mahrokh Ghoddousi Boroujeni and Clara Lucía Galimberti and Andreas Krause and Giancarlo Ferrari-Trecate},
      year={2024},
      eprint={2403.17790},
      archivePrefix={arXiv},
      primaryClass={eess.SY},
      url={https://arxiv.org/abs/2403.17790}, 
}
```

---

