# 逆向解析：大规模语言模型的可扩展激活逆向分析

发布时间：2025年06月08日

`LLM理论` `人工智能` `机器学习`

> InverseScope: Scalable Activation Inversion for Interpreting Large Language Models

# 摘要

> 理解大型语言模型（LLMs）的内部表征是可解释性研究中的核心挑战。现有的特征可解释性方法通常依赖于对表征结构的强假设，这些假设在实际中可能并不成立。在本研究中，我们引入了InverseScope，一个轻假设且可扩展的框架，用于通过输入反转来解释神经激活。给定一个目标激活，我们定义了一组生成类似激活的输入分布，并通过分析这些分布来推断编码的特征。为了应对高维空间采样效率低下的问题，我们提出了一种新型的条件生成架构，与以往方法相比，显著提高了采样效率。我们还引入了一种定量评估协议，通过计算采样输入上的特征一致性率来测试可解释性假设。InverseScope将基于反转的可解释性方法扩展到更大的模型和实际任务，使我们能够对现实世界LLMs中的内部表征进行系统化和定量化的分析。

> Understanding the internal representations of large language models (LLMs) is a central challenge in interpretability research. Existing feature interpretability methods often rely on strong assumptions about the structure of representations that may not hold in practice. In this work, we introduce InverseScope, an assumption-light and scalable framework for interpreting neural activations via input inversion. Given a target activation, we define a distribution over inputs that generate similar activations and analyze this distribution to infer the encoded features. To address the inefficiency of sampling in high-dimensional spaces, we propose a novel conditional generation architecture that significantly improves sample efficiency compared to previous methods. We further introduce a quantitative evaluation protocol that tests interpretability hypotheses using feature consistency rate computed over the sampled inputs. InverseScope scales inversion-based interpretability methods to larger models and practical tasks, enabling systematic and quantitative analysis of internal representations in real-world LLMs.

[Arxiv](https://arxiv.org/abs/2506.07406)