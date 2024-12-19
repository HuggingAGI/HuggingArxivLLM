# 破解 LVLMs 中具有视觉感知头部发散的幻觉代码

发布时间：2024年12月18日

`LLM应用` `计算机视觉` `多模态推理`

> Cracking the Code of Hallucination in LVLMs with Vision-aware Head Divergence

# 摘要

> 大型视觉语言模型（LVLMs）在融合大型语言模型（LLMs）与视觉输入方面进展显著，实现了高级的多模态推理。尽管成果斐然，但一直存在的难题是幻觉，即生成的文本无法精准反映视觉内容，从而影响了准确性和可靠性。现有的方法聚焦于对齐训练或解码优化，不过主要处理生成阶段的表象，未深挖根本缘由。在本研究中，我们探究了 LVLMs 中引发幻觉的内在机制，重点放在多头注意力模块上。具体而言，我们引入了视觉感知头差异（VHD）这一指标，用于量化注意力头输出对视觉情境的敏感度。由此，我们的发现表明存在更契合视觉信息的视觉感知注意力头；然而，模型过度依赖其先前的语言模式与幻觉紧密相关。基于这些发现，我们提出了视觉感知头强化（VHR），这是一种无需训练的方式，通过强化视觉感知注意力头的作用来减轻幻觉。大量实验显示，我们的方法在减轻幻觉方面优于前沿方法，同时保持高效，几乎不增加额外的时间成本。

> Large vision-language models (LVLMs) have made substantial progress in integrating large language models (LLMs) with visual inputs, enabling advanced multimodal reasoning. Despite their success, a persistent challenge is hallucination-where generated text fails to accurately reflect visual content-undermining both accuracy and reliability. Existing methods focus on alignment training or decoding refinements but primarily address symptoms at the generation stage without probing the underlying causes. In this work, we investigate the internal mechanisms driving hallucination in LVLMs, with an emphasis on the multi-head attention module. Specifically, we introduce Vision-aware Head Divergence (VHD), a metric that quantifies the sensitivity of attention head outputs to visual context. Based on this, our findings reveal the presence of vision-aware attention heads that are more attuned to visual information; however, the model's overreliance on its prior language patterns is closely related to hallucinations. Building on these insights, we propose Vision-aware Head Reinforcement (VHR), a training-free approach to mitigate hallucination by enhancing the role of vision-aware attention heads. Extensive experiments demonstrate that our method achieves superior performance compared to state-of-the-art approaches in mitigating hallucinations, while maintaining high efficiency with negligible additional time overhead.

[Arxiv](https://arxiv.org/abs/2412.13949)