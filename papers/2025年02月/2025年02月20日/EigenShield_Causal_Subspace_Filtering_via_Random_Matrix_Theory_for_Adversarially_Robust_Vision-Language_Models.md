# EigenShield：基于随机矩阵理论的因果子空间过滤，打造更具对抗鲁棒性的视觉语言模型。

发布时间：2025年02月20日

`LLM应用

理由：这篇论文主要探讨了视觉语言模型（VLMs）的对抗漏洞及其防御方法，属于将大型语言模型应用于多模态场景并改进其安全性的范畴，因此归类于LLM应用。` `多模态`

> EigenShield: Causal Subspace Filtering via Random Matrix Theory for Adversarially Robust Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）不仅继承了大型语言模型（LLMs）的对抗漏洞，更因多模态特性而加剧了这一问题。现有防御手段如对抗训练、输入变换和启发式检测，普遍存在计算成本高昂、架构依赖性强、易受自适应攻击等问题。为此，我们提出了EigenShield，一种基于随机矩阵理论的推理阶段防御方案。它通过量化高维VLM表示中的对抗干扰，采用 spiked covariance 模型检测结构化频谱偏差。EigenShield结合鲁棒性非符合性评分（RbNS）和分位数阈值，区分编码语义信息的因果特征向量和易受对抗 artifacts 影响的相关特征向量。通过将嵌入投影到因果子空间，EigenShield有效过滤对抗噪声，且无需修改模型参数或进行对抗训练。这种架构无关、攻击不可知的方法显著降低了攻击成功率，使频谱分析成为传统防御的可靠替代方案。实验结果表明，EigenShield在所有现有防御方法中表现最优，包括对抗训练、UNIGUARD和CIDER.

> Vision-Language Models (VLMs) inherit adversarial vulnerabilities of Large Language Models (LLMs), which are further exacerbated by their multimodal nature. Existing defenses, including adversarial training, input transformations, and heuristic detection, are computationally expensive, architecture-dependent, and fragile against adaptive attacks. We introduce EigenShield, an inference-time defense leveraging Random Matrix Theory to quantify adversarial disruptions in high-dimensional VLM representations. Unlike prior methods that rely on empirical heuristics, EigenShield employs the spiked covariance model to detect structured spectral deviations. Using a Robustness-based Nonconformity Score (RbNS) and quantile-based thresholding, it separates causal eigenvectors, which encode semantic information, from correlational eigenvectors that are susceptible to adversarial artifacts. By projecting embeddings onto the causal subspace, EigenShield filters adversarial noise without modifying model parameters or requiring adversarial training. This architecture-independent, attack-agnostic approach significantly reduces the attack success rate, establishing spectral analysis as a principled alternative to conventional defenses. Our results demonstrate that EigenShield consistently outperforms all existing defenses, including adversarial training, UNIGUARD, and CIDER.

[Arxiv](https://arxiv.org/abs/2502.14976)