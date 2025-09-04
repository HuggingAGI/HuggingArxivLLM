# 基于预训练大型语言模型的物理引导符号回归知识整合

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Knowledge Integration for Physics-informed Symbolic Regression Using Pre-trained Large Language Models

# 摘要

> 符号回归（SR）已然成为自动化科学发现的利器，能从实验数据中精准推导出控制方程。众多研究证实，将领域知识融入SR可提升所获方程的普适性与实用性。物理知情符号回归（PiSR）虽通过整合领域知识应对这一需求，但现有方法往往依赖专业公式与手动特征工程，仅限领域专家使用。本研究借助预训练大型语言模型（LLMs）推动PiSR的知识整合：利用LLMs在海量科学文献上训练出的语境理解能力，实现领域知识的自动化整合，减少手动干预，让该过程能更广泛地适用于各类科学问题。具体而言，我们将LLM集成到SR的损失函数中，新增一项LLM对SR生成方程的评估值。通过三种SR算法（DEAP、gplearn、PySR）与三种预训练LLM（Falcon、Mistral、LLama 2），在下落小球、简谐运动、电磁波三个物理动力学场景中展开全面评估。结果显示，LLM的融入持续改善了物理动力学的从数据重建效果，增强了SR模型对噪声和复杂性的鲁棒性。我们还探究了提示工程的影响，发现信息量更丰富的提示能显著提升性能。

> Symbolic regression (SR) has emerged as a powerful tool for automated scientific discovery, enabling the derivation of governing equations from experimental data. A growing body of work illustrates the promise of integrating domain knowledge into the SR to improve the discovered equation's generality and usefulness. Physics-informed SR (PiSR) addresses this by incorporating domain knowledge, but current methods often require specialized formulations and manual feature engineering, limiting their adaptability only to domain experts. In this study, we leverage pre-trained Large Language Models (LLMs) to facilitate knowledge integration in PiSR. By harnessing the contextual understanding of LLMs trained on vast scientific literature, we aim to automate the incorporation of domain knowledge, reducing the need for manual intervention and making the process more accessible to a broader range of scientific problems. Namely, the LLM is integrated into the SR's loss function, adding a term of the LLM's evaluation of the SR's produced equation. We extensively evaluate our method using three SR algorithms (DEAP, gplearn, and PySR) and three pre-trained LLMs (Falcon, Mistral, and LLama 2) across three physical dynamics (dropping ball, simple harmonic motion, and electromagnetic wave). The results demonstrate that LLM integration consistently improves the reconstruction of physical dynamics from data, enhancing the robustness of SR models to noise and complexity. We further explore the impact of prompt engineering, finding that more informative prompts significantly improve performance.

[Arxiv](https://arxiv.org/abs/2509.03036)