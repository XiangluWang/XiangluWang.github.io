---
title: 'Exploring The Forgetting in Adversarial Training: A Novel Method for Enhancing Robustness'
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about adversarial training and continual learning.'
date: 2025-01-23
venue: "The Thirteenth International Conference on Learning Representations (ICLR'25)"
paperurl: 'https://openreview.net/pdf?id=fjPOt8QlqQ'
citation: 'Wang, Xianglu, and Hu Ding. "Exploring The Forgetting in Adversarial Training: A Novel Method for Enhancing Robustness." The Thirteenth International Conference on Learning Representations.'
---

In recent years, there has been an explosion of research into developing
robust deep neural networks against adversarial examples. As one of the most successful methods, \textit{Adversarial Training (AT)}  has been widely studied before,
but there is still a gap to achieve promising
clean and robust accuracy for many practical tasks. In this paper, we
consider the AT problem from a new perspective which connects it to \textit{catastrophic forgetting} in continual learning (CL). 
Catastrophic forgetting is a phenomenon in which neural networks forget old knowledge upon learning a new task. Although AT and CL are two different problems, we show that they actually share several  key properties in their training processes. Specifically, we conduct an empirical study and find that this forgetting phenomenon indeed occurs in adversarial robust training across multiple datasets (SVHN, CIFAR-10, CIFAR-100, and TinyImageNet) and perturbation models ($\ell_{\infty}$ and $\ell_{2}$). Based on this observation, we propose a novel method called \textbf{A}daptive \textbf{M}ulti-teachers \textbf{S}elf-distillation (\textbf{AMS}), which leverages a carefully designed adaptive regularizer to mitigate the forgetting by aligning model outputs between new and old ``stages''. Moreover, our approach can be used  as a unified method to enhance multiple different AT algorithms. Our experiments demonstrate that our method can significantly enhance robust accuracy and meanwhile preserve high clean accuracy, under several popular adversarial attacks (e.g., PGD, CW, and Auto Attacks). As another benefit of our method, we discover that it can largely alleviate the robust overfitting issue of AT in our experiments.
