# 《谁带来了飞盘：借因果分析探寻大型视觉语言模型中的隐匿幻觉因素》

发布时间：2024年12月03日

`LLM应用` `视觉语言模型` `幻觉探测`

> Who Brings the Frisbee: Probing Hidden Hallucination Factors in Large Vision-Language Model via Causality Analysis

# 摘要

> 近期，大型视觉语言模型（LVLM）取得的进步显著提升了其理解视觉输入与自然语言的能力。然而，在现实应用中，LVLM面临的一大挑战是产生幻觉，即生成不存在的视觉元素，这削弱了用户的信任。驱动这种多模态幻觉的潜在机制尚不明确。极少有研究阐明诸如天空、树木或草地等情境是否会致使LVLM产生飞盘的幻觉。我们推测，诸如物体、情境和语义前景-背景结构等隐藏因素会引发幻觉。本研究提出了一种新颖的因果方法：一个幻觉探测系统，用于识别这些隐藏因素。通过分析图像、文本提示和网络显著度之间的因果关系，我们系统地探索了阻断这些因素的干预措施。我们的实验发现，基于我们的分析的一种直接技术能够显著减少幻觉。此外，我们的分析表明，编辑网络内部以最小化幻觉输出具有可能性。

> Recent advancements in large vision-language models (LVLM) have significantly enhanced their ability to comprehend visual inputs alongside natural language. However, a major challenge in their real-world application is hallucination, where LVLMs generate non-existent visual elements, eroding user trust. The underlying mechanism driving this multimodal hallucination is poorly understood. Minimal research has illuminated whether contexts such as sky, tree, or grass field involve the LVLM in hallucinating a frisbee. We hypothesize that hidden factors, such as objects, contexts, and semantic foreground-background structures, induce hallucination. This study proposes a novel causal approach: a hallucination probing system to identify these hidden factors. By analyzing the causality between images, text prompts, and network saliency, we systematically explore interventions to block these factors. Our experimental findings show that a straightforward technique based on our analysis can significantly reduce hallucinations. Additionally, our analyses indicate the potential to edit network internals to minimize hallucinated outputs.

[Arxiv](https://arxiv.org/abs/2412.02946)