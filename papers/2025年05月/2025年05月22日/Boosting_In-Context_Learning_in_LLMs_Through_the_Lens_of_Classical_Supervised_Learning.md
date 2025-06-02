# 从经典监督学习的角度增强LLMs中的上下文学习能力

发布时间：2025年05月22日

`LLM理论` `机器学习`

> Boosting In-Context Learning in LLMs Through the Lens of Classical Supervised Learning

# 摘要

> 在上下文学习 (ICL) 中，大型语言模型 (LLMs) 仅需少量示例即可适应新任务，但其预测结果往往存在系统性偏差，导致分类性能不稳定。虽然有校准技术被提出以缓解这些偏差，但我们发现，在 logit 空间中，许多这些方法等同于仅仅平移 LLM 的决策边界，而无法改变其方向。当偏差导致 LLM 严重误判时，这种方法证明是不足的。为了解决这些限制并提供一个统一的框架，我们提出了 Supervised Calibration (SC)，这是一个基于损失最小化的框架，能够在 logit 空间中学习 LLM 预测概率的最优、按类别仿射变换，而无需额外的外部数据。通过采用更丰富的函数类，SC 不仅将 ICL 中许多现有的校准方法作为特例涵盖，还能够改变甚至完全反转 LLM 决策边界的朝向。此外，SC 的损失函数性质使其能够无缝集成两种专门设计的正则化技术：上下文不变量和方向信任区域。前者旨在解决 ICL 中的稳定性问题，而后者则控制校准的程度。最后，SC 在 Mistral-7B-Instruct-v0.3、LLaMA-2-7B-chat 和 Qwen2-7B-Instruct 的 4-shot、8-shot 和 16-shot 设置下的所有九个数据集上，均超越了校准基线模型，达到了最先进的性能水平。

> In-Context Learning (ICL) allows Large Language Models (LLMs) to adapt to new tasks with just a few examples, but their predictions often suffer from systematic biases, leading to unstable performances in classification. While calibration techniques are proposed to mitigate these biases, we show that, in the logit space, many of these methods are equivalent to merely shifting the LLM's decision boundary without having the ability to alter its orientation. This proves inadequate when biases cause the LLM to be severely misdirected. To address these limitations and provide a unifying framework, we propose Supervised Calibration (SC), a loss-minimization based framework which learns an optimal, per-class affine transformation of the LLM's predictive probabilities in the logit space without requiring external data beyond the context. By using a more expressive functional class, SC not only subsumes many existing calibration methods in ICL as special cases, but also enables the ability to alter and even completely reverse the orientation of the LLM's decision boundary. Furthermore, SC's loss-based nature facilitates the seamless integration of two purpose-built regularization techniques: context-invariance and directional trust-region. The former is designed to tackle the instability issue in ICL, while the latter controls the degree of calibration. Finally, SC delivers state-of-the-art performance over calibration baselines in the 4-shot, 8-shot, and 16-shot settings across all nine datasets for Mistral-7B-Instruct-v0.3, LLaMA-2-7B-chat, and Qwen2-7B-Instruct.

[Arxiv](https://arxiv.org/abs/2505.23783)