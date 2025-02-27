# RewardDS：基于奖励驱动的数据合成实现大型语言模型的隐私保护微调

发布时间：2025年02月22日

`LLM应用`

> RewardDS: Privacy-Preserving Fine-Tuning for Large Language Models via Reward Driven Data Synthesis

# 摘要

> 大型语言模型（LLMs）的成功吸引了许多人通过上传数据来微调它们，以适应特定领域的任务。然而，在医疗和金融等敏感领域，隐私问题常常引发关注。为了解决这一问题，我们提出了RewardDS，这是一种新型的隐私保护框架，通过微调奖励代理模型，并利用奖励信号来指导合成数据的生成。我们的RewardDS引入了两个关键模块：Reward Guided Filtering和Self-Optimizing Refinement，这两个模块能够同时过滤和优化合成数据，从而有效缓解噪声问题。在医疗、金融和代码生成等多个领域的广泛实验表明了我们方法的有效性。

> The success of large language models (LLMs) has attracted many individuals to fine-tune them for domain-specific tasks by uploading their data. However, in sensitive areas like healthcare and finance, privacy concerns often arise. One promising solution is to sample synthetic data with Differential Privacy (DP) guarantees to replace private data. However, these synthetic data contain significant flawed data, which are considered as noise. Existing solutions typically rely on naive filtering by comparing ROUGE-L scores or embedding similarities, which are ineffective in addressing the noise. To address this issue, we propose RewardDS, a novel privacy-preserving framework that fine-tunes a reward proxy model and uses reward signals to guide the synthetic data generation. Our RewardDS introduces two key modules, Reward Guided Filtering and Self-Optimizing Refinement, to both filter and refine the synthetic data, effectively mitigating the noise. Extensive experiments across medical, financial, and code generation domains demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2502.18517)