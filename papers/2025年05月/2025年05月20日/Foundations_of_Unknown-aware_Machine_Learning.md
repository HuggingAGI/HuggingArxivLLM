# 感知未知的机器学习基础

发布时间：2025年05月20日

`LLM理论` `AI安全` `机器学习`

> Foundations of Unknown-aware Machine Learning

# 摘要

> # 摘要  
在开放世界部署中确保机器学习模型的可靠性和安全性是 AI 安全领域的核心挑战。本论文从传统神经网络到现代大型语言模型（LLMs）等基础模型出发，构建了算法和理论基础，以应对分布偏移和未知类别带来的关键可靠性问题。

传统学习范式，如经验风险最小化（ERM），假设训练和推理阶段的数据分布一致，这在处理分布外（OOD）输入时往往导致过度自信的预测。本论文提出了一种新型框架，旨在同时优化分布内准确性和对未知数据的可靠性。核心贡献在于开发了一种基于未知感知的学习框架，使模型无需标注的OOD数据即可识别和处理新型输入。

我们提出了新的离群值生成方法 VOS、NPOS 和 DREAM-OOD，用于在训练过程中生成具有信息量的未知样本。在此基础上，我们提出了 SAL，这是一个理论与算法结合的框架，利用未标注的真实世界数据提升实际部署条件下的OOD检测能力。这些方法证明，丰富的未标注数据可以被有效利用，以识别和适应不可预见的输入，并提供形式化的可靠性保证。

本论文还将可靠学习扩展到基础模型。我们开发了 HaloScope 用于检测 LLM 中的幻觉，MLLMGuard 用于防御多模态模型中的恶意提示，以及数据清洗方法，用于去除人类反馈中的噪声，以实现更好的对齐。这些工具针对威胁大规模模型安全的失效模式。

总体而言，这些贡献推动了未知感知学习作为一种新范式，并希望它能在尽量减少人工干预的情况下，提升 AI 系统的可靠性。


> Ensuring the reliability and safety of machine learning models in open-world deployment is a central challenge in AI safety. This thesis develops both algorithmic and theoretical foundations to address key reliability issues arising from distributional uncertainty and unknown classes, from standard neural networks to modern foundation models like large language models (LLMs).
  Traditional learning paradigms, such as empirical risk minimization (ERM), assume no distribution shift between training and inference, often leading to overconfident predictions on out-of-distribution (OOD) inputs. This thesis introduces novel frameworks that jointly optimize for in-distribution accuracy and reliability to unseen data. A core contribution is the development of an unknown-aware learning framework that enables models to recognize and handle novel inputs without labeled OOD data.
  We propose new outlier synthesis methods, VOS, NPOS, and DREAM-OOD, to generate informative unknowns during training. Building on this, we present SAL, a theoretical and algorithmic framework that leverages unlabeled in-the-wild data to enhance OOD detection under realistic deployment conditions. These methods demonstrate that abundant unlabeled data can be harnessed to recognize and adapt to unforeseen inputs, providing formal reliability guarantees.
  The thesis also extends reliable learning to foundation models. We develop HaloScope for hallucination detection in LLMs, MLLMGuard for defending against malicious prompts in multimodal models, and data cleaning methods to denoise human feedback used for better alignment. These tools target failure modes that threaten the safety of large-scale models in deployment.
  Overall, these contributions promote unknown-aware learning as a new paradigm, and we hope it can advance the reliability of AI systems with minimal human efforts.

[Arxiv](https://arxiv.org/abs/2505.14933)