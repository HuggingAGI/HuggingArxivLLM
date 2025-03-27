# GAPO：利用生成对抗策略优化学习偏好提示

发布时间：2025年03月25日

`LLM应用` `人工智能`

> GAPO: Learning Preferential Prompt through Generative Adversarial Policy Optimization

# 摘要

> 大型语言模型的最新进展凸显了通过预定义约束精准控制模型输出的迫切需求。现有方法虽尝试通过直接指令-响应合成或偏好响应优化来实现，但往往在理解与适应约束方面力有未逮。这一局限性在处理精细粒度约束时尤为突出，常导致模型出现幻觉或表现脆化。我们提出了一种名为生成式对抗策略优化（GAPO）的创新框架，该框架巧妙结合了基于GAN的训练动力学与编码器专属奖励模型，旨在逐步学习并适应日益复杂的约束条件。GAPO借助对抗训练机制，能够自动生成难度各异的训练样本，同时通过编码器专属架构更好地捕捉提示-响应间的关系。大量实验结果表明，GAPO在多个基准测试中均表现出色，尤其在需要精细粒度约束处理的场景下，其性能远超现有方法如PPO、DPO和KTO。我们的研究结果表明，GAPO独特的偏好提示学习方法为控制LLM输出提供了一种更稳健且高效的解决方案。代码可在GitHub上获取：https://github.com/MikeGu721/GAPO.

> Recent advances in large language models have highlighted the critical need for precise control over model outputs through predefined constraints. While existing methods attempt to achieve this through either direct instruction-response synthesis or preferential response optimization, they often struggle with constraint understanding and adaptation. This limitation becomes particularly evident when handling fine-grained constraints, leading to either hallucination or brittle performance. We introduce Generative Adversarial Policy Optimization (GAPO), a novel framework that combines GAN-based training dynamics with an encoder-only reward model to progressively learn and adapt to increasingly complex constraints. GAPO leverages adversarial training to automatically generate training samples of varying difficulty while utilizing the encoder-only architecture to better capture prompt-response relationships. Extensive experiments demonstrate GAPO's superior performance across multiple benchmarks, particularly in scenarios requiring fine-grained constraint handling, where it significantly outperforms existing methods like PPO, DPO, and KTO. Our results suggest that GAPO's unique approach to preferential prompt learning offers a more robust and effective solution for controlling LLM outputs. Code is avaliable in https://github.com/MikeGu721/GAPO.

[Arxiv](https://arxiv.org/abs/2503.20194)