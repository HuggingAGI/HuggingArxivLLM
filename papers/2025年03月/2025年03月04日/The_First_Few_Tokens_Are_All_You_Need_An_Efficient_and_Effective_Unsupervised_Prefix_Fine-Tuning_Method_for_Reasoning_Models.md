# 前缀即精华：推理模型高效无监督微调新方法

发布时间：2025年03月04日

`LLM理论` `人工智能`

> The First Few Tokens Are All You Need: An Efficient and Effective Unsupervised Prefix Fine-Tuning Method for Reasoning Models

# 摘要

> 提升大型语言模型的推理能力，传统方法往往依赖标注数据的监督微调或高计算成本的采样。我们提出了一种无监督前缀微调方法（UPFT），该方法基于“前缀自洽性”这一观察——即不同解题路径间共享的初始推理步骤——来提升模型的推理效率。通过仅在初始前缀子字符串（最少8个token）上进行训练，UPFT完全摆脱了对标注数据或耗尽式采样的依赖。在推理基准上的实验结果表明，UPFT的性能可与监督方法如拒绝采样微调相媲美，同时将训练时间减少了75%，采样成本降低了99%。进一步的分析揭示，推理过程中的错误往往出现在后期阶段，而基于前缀的训练方法能够有效保留模型的结构化知识。这项研究证明，通过最小的无监督微调，可以在大型语言模型中实现显著的推理能力提升，为传统方法提供了一种既可扩展又资源高效的替代方案。

> Improving the reasoning capabilities of large language models (LLMs) typically requires supervised fine-tuning with labeled data or computationally expensive sampling. We introduce Unsupervised Prefix Fine-Tuning (UPFT), which leverages the observation of Prefix Self-Consistency -- the shared initial reasoning steps across diverse solution trajectories -- to enhance LLM reasoning efficiency. By training exclusively on the initial prefix substrings (as few as 8 tokens), UPFT removes the need for labeled data or exhaustive sampling. Experiments on reasoning benchmarks show that UPFT matches the performance of supervised methods such as Rejection Sampling Fine-Tuning, while reducing training time by 75% and sampling cost by 99%. Further analysis reveals that errors tend to appear in later stages of the reasoning process and that prefix-based training preserves the model's structural knowledge. This work demonstrates how minimal unsupervised fine-tuning can unlock substantial reasoning gains in LLMs, offering a scalable and resource-efficient alternative to conventional approaches.

[Arxiv](https://arxiv.org/abs/2503.02875)