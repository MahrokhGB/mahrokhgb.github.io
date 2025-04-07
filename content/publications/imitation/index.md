---
title: "Contractive Dynamical Imitation Policies for Efficient Out-of-Sample Recovery"
date: 2024-12-10
lastmod: 2025-03-26
tags: ["Learning from demonstrations", "Safe imitation learning", "Robotics", "Dynamical systems", "Contraction theory"]
author: ["Amin Abyaneh", "Mahrokh G. Boroujeni", "Hsiu-chin Lin", "Giancarlo Ferrari-Trecate"]
description: "This paper presents a framework for learning imitation policies using contractive dynamical systems to ensure reliable behavior, even in out-of-sample situations. It uses recurrent equilibrium networks and coupling layers to guarantee contractivity under any parameters, allowing for unconstrained optimization. The approach includes theoretical performance bounds and shows strong empirical results on simulated robotic manipulation and navigation tasks. In International Conference on Learning Representations, 2025."
summary: "This paper presents a framework for learning imitation policies using contractive dynamical systems to ensure reliable behavior, even in out-of-sample situations. It uses recurrent equilibrium networks and coupling layers to guarantee contractivity under any parameters, allowing for unconstrained optimization. The approach includes theoretical performance bounds and shows strong empirical results on simulated robotic manipulation and navigation tasks."
cover:
    Image: "scds_eimreal.pdf"
    alt: "Sim-to-Real"
    relative: false
editPost:
    URL: "https://sites.google.com/view/contractive-dynamical-policies"
    Text: "International Conference on Learning Representations (ICLR)"

---

---

##### Download

+ [Paper](SCDS.pdf)

---

##### Abstract

Imitation learning is a data-driven approach to learning policies from expert behavior, but it is prone to unreliable outcomes in out-of-sample (OOS) regions. While previous research relying on stable dynamical systems guarantees convergence to a desired state, it often overlooks transient behavior. We propose a framework for learning policies modeled by contractive dynamical systems, ensuring that all policy rollouts converge regardless of perturbations, and in turn, enable efficient OOS recovery. By leveraging recurrent equilibrium networks and coupling layers, the policy structure guarantees contractivity for any parameter choice, which facilitates unconstrained optimization. We also provide theoretical upper bounds for worst-case and expected loss to rigorously establish the reliability of our method in deployment. Empirically, we demonstrate substantial OOS performance improvements for simulated robotic manipulation and navigation tasks.

---

##### Image: Simulations

![](scds_simreal.pdf)

---

##### Citation

Abyaneh, A., Boroujeni, M. G., Lin, H. C., & Ferrari-Trecate, G. (2024). Contractive Dynamical Imitation Policies for Efficient Out-of-Sample Recovery. arXiv preprint arXiv:2412.07544.

```BibTeX
@misc{abyaneh2025contractivedynamicalimitationpolicies,
      title={Contractive Dynamical Imitation Policies for Efficient Out-of-Sample Recovery}, 
      author={Amin Abyaneh and Mahrokh G. Boroujeni and Hsiu-Chin Lin and Giancarlo Ferrari-Trecate},
      year={2025},
      eprint={2412.07544},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2412.07544}, 
}
```

---

