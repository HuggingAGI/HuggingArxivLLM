# # 从经典监督学习视角提升大型语言模型的上下文学习能力
通过经典监督学习的视角，我们探讨了如何提升大型语言模型中的上下文学习能力。

发布时间：2025年05月22日

`LLM理论` `机器学习`

> Boosting In-Context Learning in LLMs Through the Lens of Classical Supervised Learning

# 摘要

> 上下文学习（ICL）使大型语言模型（LLMs）能够仅通过几个示例适应新任务，但它们的预测通常会受到系统性偏差的影响，导致分类性能不稳定。尽管提出了各种校准技术来缓解这些偏差，但我们发现，在logit空间中，许多这些方法等价于仅仅平移LLMs的决策边界，而无法改变其方向。这在偏差导致LLMs严重误判的情况下证明是不够的。

为了解决这些限制并提供一个统一的框架，我们提出了监督校准（SC），这是一种基于损失最小化的框架，能够在logit空间中学习LLMs预测概率的最优、每类仿射变换，而无需额外的上下文外数据。通过采用更丰富的函数类，SC不仅将ICL中许多现有的校准方法作为特殊情况涵盖，还能够改变甚至完全反转LLMs决策边界的定向。

此外，SC基于损失的性质使其能够无缝集成两种专门设计的正则化技术：上下文不变性和方向信任域。前者旨在解决ICL中的不稳定性问题，而后者控制校准的程度。最后，SC在Mistral-7B-Instruct-v0.3、LLaMA-2-7B-chat和Qwen2-7B-Instruct的所有九个数据集的4-shot、8-shot和16-shot设置下，均超越了校准基线，达到了最先进水平的性能。

> In-Context Learning (ICL) allows Large Language Models (LLMs) to adapt to new tasks with just a few examples, but their predictions often suffer from systematic biases, leading to unstable performances in classification. While calibration techniques are proposed to mitigate these biases, we show that, in the logit space, many of these methods are equivalent to merely shifting the LLM's decision boundary without having the ability to alter its orientation. This proves inadequate when biases cause the LLM to be severely misdirected. To address these limitations and provide a unifying framework, we propose Supervised Calibration (SC), a loss-minimization based framework which learns an optimal, per-class affine transformation of the LLM's predictive probabilities in the logit space without requiring external data beyond the context. By using a more expressive functional class, SC not only subsumes many existing calibration methods in ICL as special cases, but also enables the ability to alter and even completely reverse the orientation of the LLM's decision boundary. Furthermore, SC's loss-based nature facilitates the seamless integration of two purpose-built regularization techniques: context-invariance and directional trust-region. The former is designed to tackle the instability issue in ICL, while the latter controls the degree of calibration. Finally, SC delivers state-of-the-art performance over calibration baselines in the 4-shot, 8-shot, and 16-shot settings across all nine datasets for Mistral-7B-Instruct-v0.3, LLaMA-2-7B-chat, and Qwen2-7B-Instruct.

[Arxiv](https://arxiv.org/abs/2505.23783)