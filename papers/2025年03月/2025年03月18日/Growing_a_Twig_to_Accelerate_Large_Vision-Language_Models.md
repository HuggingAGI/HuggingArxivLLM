# 培育嫩枝加速大型视觉语言模型

发布时间：2025年03月18日

`LLM应用` `多模态`

> Growing a Twig to Accelerate Large Vision-Language Models

# 摘要

> 大型视觉语言模型（VLMs）在开放世界的多模态理解方面表现出色，但其高昂的计算成本为实际应用带来了挑战。近期研究通过剪枝VLM早期层注意力图指导下的冗余视觉token来加速VLM。尽管这些方法取得了一定成功，但仍存在两个主要问题：(i) 早期层注意力信号不敏感导致精度显著下降，以及(ii) 在生成长响应（如30个token）时加速效果有限。为解决这些问题，我们提出了TwigVLM——一种简单通用的架构，通过在基础VLM的早期层上添加轻量级分支twig。与现有仅基于视觉token剪枝的VLM加速方法不同，TwigVLM不仅通过twig指导的token剪枝（TTP）策略实现了更好的精度保留，还通过自推测解码（SSD）策略提升了生成速度。以LLaVA-1.5-7B为基础VLM，实验结果显示，在剪枝88.9%视觉token后，TwigVLM仍保留96%的原始性能，并在生成长响应时实现154%的加速，显著优于现有VLM加速方法。代码即将公开发布。

> Large vision-language models (VLMs) have demonstrated remarkable capabilities in open-world multimodal understanding, yet their high computational overheads pose great challenges for practical deployment. Some recent works have proposed methods to accelerate VLMs by pruning redundant visual tokens guided by the attention maps of VLM's early layers. Despite the success of these token pruning methods, they still suffer from two major shortcomings: (i) considerable accuracy drop due to insensitive attention signals in early layers, and (ii) limited speedup when generating long responses (e.g., 30 tokens). To address the limitations above, we present TwigVLM -- a simple and general architecture by growing a lightweight twig upon an early layer of the base VLM. Compared with most existing VLM acceleration methods purely based on visual token pruning, our TwigVLM not only achieves better accuracy retention by employing a twig-guided token pruning (TTP) strategy, but also yields higher generation speed by utilizing a self-speculative decoding (SSD) strategy. Taking LLaVA-1.5-7B as the base VLM, experimental results show that TwigVLM preserves 96% of the original performance after pruning 88.9% of visual tokens and achieves 154% speedup in generating long responses, delivering significantly better performance in terms of both accuracy and speed over the state-of-the-art VLM acceleration methods. Code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2503.14075)