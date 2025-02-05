# 避免虚假的锐度最小化，SAM的适用性更广

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要讨论了Sharpness Aware Minimization (SAM) 在自然语言处理 (NLP) 领域的表现，并提出了一种新算法 Functional-SAM 来改进曲率正则化技术在大型语言模型 (LLMs) 中的应用。论文的核心内容集中在优化算法的理论改进和其在LLM中的应用效果，因此属于LLM理论范畴。` `机器学习`

> Avoiding spurious sharpness minimization broadens applicability of SAM

# 摘要

> # 摘要
Sharpness Aware Minimization (SAM) 等曲率正则化技术在视觉任务中展现了显著的泛化提升潜力。然而，SAM 在自然语言处理 (NLP) 领域表现欠佳，甚至可能降低性能 —— 即便计算资源翻倍。我们深入研究了这一跨领域差异，发现 SAM 在 NLP 中主要依赖于 logit 统计的正则化，而非优化函数本身的几何结构。基于这一发现，我们提出了一种新算法 Functional-SAM，它通过调整神经网络整体函数的统计特性来正则化曲率，避免了 logit 操作带来的虚假最小化。此外，我们还发现对 SAM 扰动进行预处理也能防止虚假最小化，与 Functional-SAM 结合后，性能进一步提升。在固定长度和 Chinchilla 风格的训练设置中，经过相同步数的训练后，我们的算法在多种模型规模（包括十亿参数级别）下均优于 AdamW 和 SAM 基线。总体而言，我们的研究强调了精确描述锐度对于扩展曲率正则化在大型语言模型 (LLMs) 中应用的重要性。

> Curvature regularization techniques like Sharpness Aware Minimization (SAM) have shown great promise in improving generalization on vision tasks. However, we find that SAM performs poorly in domains like natural language processing (NLP), often degrading performance -- even with twice the compute budget. We investigate the discrepancy across domains and find that in the NLP setting, SAM is dominated by regularization of the logit statistics -- instead of improving the geometry of the function itself. We use this observation to develop an alternative algorithm we call Functional-SAM, which regularizes curvature only through modification of the statistics of the overall function implemented by the neural network, and avoids spurious minimization through logit manipulation. Furthermore, we argue that preconditioning the SAM perturbation also prevents spurious minimization, and when combined with Functional-SAM, it gives further improvements. Our proposed algorithms show improved performance over AdamW and SAM baselines when trained for an equal number of steps, in both fixed-length and Chinchilla-style training settings, at various model scales (including billion-parameter scale). On the whole, our work highlights the importance of more precise characterizations of sharpness in broadening the applicability of curvature regularization to large language models (LLMs).

[Arxiv](https://arxiv.org/abs/2502.02407)