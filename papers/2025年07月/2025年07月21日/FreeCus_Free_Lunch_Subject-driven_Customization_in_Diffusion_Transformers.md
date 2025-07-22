# FreeCus：主题驱动的扩散Transformer免费午餐式定制

发布时间：2025年07月21日

`LLM应用` `计算机视觉` `图像生成`

> FreeCus: Free Lunch Subject-driven Customization in Diffusion Transformers

# 摘要

> 基于近期文本到图像生成领域的重大突破，特别是扩散变压器（DiT）的出现，以主题为中心的技术正在推动高保真定制化生产，确保从参考输入中保留主体身份，从而实现激动人心的设计流程和引人入胜的娱乐体验。然而，现有解决方案通常需要通过可训练的文本嵌入进行针对每个主题的优化，或者在大规模数据集上训练专门的编码器来提取主体特征。这种对训练流程的依赖从根本上限制了它们的实际应用。更重要的是，当前方法未能充分挖掘现代扩散变压器（如Flux系列）固有的零样本潜力，用于真实的主体驱动合成。为解决这一问题，我们提出了FreeCus，一个真正无需训练的框架，通过三项关键创新激活DiT的能力：1) 我们引入了一种关键注意力共享机制，既捕捉主体的布局完整性，又保留关键编辑灵活性。2) 通过对DiT动态位移的简单分析，我们提出了一种改进的变体，显著提升了细粒度特征提取能力。3) 我们进一步整合了先进的多模态大语言模型（MLLMs），以丰富跨模态语义表示。大量实验表明，我们的方法成功解锁了DiT的零样本能力，在不同上下文中实现一致的主体合成，达到或超越了需要额外训练的方法的最先进水平。值得注意的是，我们的框架与现有的 inpainting 管道和控制模块无缝兼容，从而提供了更引人入胜的体验。我们的代码可在以下地址获取：https://github.com/Monalissaa/FreeCus。

> In light of recent breakthroughs in text-to-image (T2I) generation, particularly with diffusion transformers (DiT), subject-driven technologies are increasingly being employed for high-fidelity customized production that preserves subject identity from reference inputs, enabling thrilling design workflows and engaging entertainment. Existing alternatives typically require either per-subject optimization via trainable text embeddings or training specialized encoders for subject feature extraction on large-scale datasets. Such dependencies on training procedures fundamentally constrain their practical applications. More importantly, current methodologies fail to fully leverage the inherent zero-shot potential of modern diffusion transformers (e.g., the Flux series) for authentic subject-driven synthesis. To bridge this gap, we propose FreeCus, a genuinely training-free framework that activates DiT's capabilities through three key innovations: 1) We introduce a pivotal attention sharing mechanism that captures the subject's layout integrity while preserving crucial editing flexibility. 2) Through a straightforward analysis of DiT's dynamic shifting, we propose an upgraded variant that significantly improves fine-grained feature extraction. 3) We further integrate advanced Multimodal Large Language Models (MLLMs) to enrich cross-modal semantic representations. Extensive experiments reflect that our method successfully unlocks DiT's zero-shot ability for consistent subject synthesis across diverse contexts, achieving state-of-the-art or comparable results compared to approaches that require additional training. Notably, our framework demonstrates seamless compatibility with existing inpainting pipelines and control modules, facilitating more compelling experiences. Our code is available at: https://github.com/Monalissaa/FreeCus.

[Arxiv](https://arxiv.org/abs/2507.15249)