# 数据增强如何影响大型语言模型的置信度评估

发布时间：2025年05月21日

`LLM应用` `人工智能` `模型评估`

> The Effects of Data Augmentation on Confidence Estimation for LLMs

# 摘要

> 评估大型语言模型（LLMs）的可靠性，尤其是广泛应用的闭源模型，置信度估计至关重要。虽然数据增强可用于置信度估计，但现有讨论多集中于特定增强技术，限制了其潜力。我们研究了不同数据增强方法对置信度估计的影响，发现数据增强策略可有效提升性能并缓解过度自信的影响。进一步研究发现，保持语义信息的同时，增加数据多样性能显著提升增强效果。此外，不同增强策略在不同应用场景中的表现存在显著差异。综合考虑参数可迁移性和实用性，随机组合的增强方式是一个引人注目的选择。

> Confidence estimation is crucial for reflecting the reliability of large language models (LLMs), particularly in the widely used closed-source models. Utilizing data augmentation for confidence estimation is viable, but discussions focus on specific augmentation techniques, limiting its potential. We study the impact of different data augmentation methods on confidence estimation. Our findings indicate that data augmentation strategies can achieve better performance and mitigate the impact of overconfidence. We investigate the influential factors related to this and discover that, while preserving semantic information, greater data diversity enhances the effectiveness of augmentation. Furthermore, the impact of different augmentation strategies varies across different range of application. Considering parameter transferability and usability, the random combination of augmentations is a promising choice.

[Arxiv](https://arxiv.org/abs/2506.11046)