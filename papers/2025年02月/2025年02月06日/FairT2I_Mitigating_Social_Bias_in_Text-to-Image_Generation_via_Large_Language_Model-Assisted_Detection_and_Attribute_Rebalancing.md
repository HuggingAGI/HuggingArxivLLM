# FairT2I: 利用大型语言模型辅助检测与属性再平衡，缓解文本生成图像中的社会偏见

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来检测和缓解文本到图像（T2I）生成模型中的社会偏见。论文提出的FairT2I框架包含基于LLM的偏见检测模块，这表明LLM被直接应用于解决T2I模型中的伦理问题。因此，这篇论文属于LLM应用类别。` `内容创作`

> FairT2I: Mitigating Social Bias in Text-to-Image Generation via Large Language Model-Assisted Detection and Attribute Rebalancing

# 摘要

> # 摘要
文本到图像（T2I）模型的广泛应用彻底革新了内容创作，为艺术表达、教育材料开发和营销等多样化应用提供了强大工具。然而，这些模型依赖的大规模数据集往往包含社会偏见，引发了严重的伦理问题。当AI生成内容被纳入训练数据时，这些偏见可能被放大，导致生成结果中刻板印象的强化和延续。本文提出FairT2I框架，利用大型语言模型检测并缓解T2I生成中的社会偏见。该框架包含两大核心模块：（1）基于LLM的偏见检测模块，通过文本提示识别生成图像中的潜在社会偏见；（2）属性重新平衡模块，通过微调T2I模型中的敏感属性来减轻已识别的偏见。我们在多个T2I模型和数据集上的实验表明，FairT2I在保持高质量图像生成的同时，显著减少了偏见。基于Stable Bias研究中的职业数据集，我们通过定性用户研究和定量非参数分析验证了FairT2I的有效性。结果显示，FairT2I成功减轻了社会偏见，并提升了生成图像中敏感属性的多样性。此外，我们使用P2数据集证明，该框架能够检测到人类难以察觉的微妙偏见，超越了职业相关提示的范畴。基于这些发现，我们提出了一个新的基准数据集，用于评估T2I模型中的偏见。

> The proliferation of Text-to-Image (T2I) models has revolutionized content creation, providing powerful tools for diverse applications ranging from artistic expression to educational material development and marketing. Despite these technological advancements, significant ethical concerns arise from these models' reliance on large-scale datasets that often contain inherent societal biases. These biases are further amplified when AI-generated content is included in training data, potentially reinforcing and perpetuating stereotypes in the generated outputs. In this paper, we introduce FairT2I, a novel framework that harnesses large language models to detect and mitigate social biases in T2I generation. Our framework comprises two key components: (1) an LLM-based bias detection module that identifies potential social biases in generated images based on text prompts, and (2) an attribute rebalancing module that fine-tunes sensitive attributes within the T2I model to mitigate identified biases. Our extensive experiments across various T2I models and datasets show that FairT2I can significantly reduce bias while maintaining high-quality image generation. We conducted both qualitative user studies and quantitative non-parametric analyses in the generated image feature space, building upon the occupational dataset introduced in the Stable Bias study. Our results show that FairT2I successfully mitigates social biases and enhances the diversity of sensitive attributes in generated images. We further demonstrate, using the P2 dataset, that our framework can detect subtle biases that are challenging for human observers to perceive, extending beyond occupation-related prompts. On the basis of these findings, we introduce a new benchmark dataset for evaluating bias in T2I models.

[Arxiv](https://arxiv.org/abs/2502.03826)