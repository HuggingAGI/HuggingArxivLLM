# 内部激活修正：无需更新参数，保护视觉语言模型

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了视觉语言模型（VLMs）在生成有害内容方面的问题，并提出了一种内部激活修正方法来提升模型的安全性。虽然涉及到了大型语言模型（LLMs）的安全对齐机制，但研究的核心是VLMs的应用和改进，特别是如何通过修正激活来提高模型的安全性。因此，这篇论文应归类为LLM应用。` `人工智能`

> Internal Activation Revision: Safeguarding Vision Language Models Without Parameter Update

# 摘要

> # 摘要
视觉语言模型（VLMs）虽然具备强大的多模态能力，但相比其基础的大型语言模型（LLMs），更容易生成有害内容。我们的研究发现，图像的引入在模型前向传播过程中显著改变了内部激活，与文本输入触发的激活不同。此外，VLMs中嵌入的LLMs的安全对齐机制不足以应对这些激活差异，使得模型容易受到简单的越狱攻击。为此，我们提出了一种	extbf{内部激活修正}方法，在生成过程中高效修正激活，引导模型生成更安全的输出。我们的框架在层和头级别引入修正，提供了对模型生成的多粒度控制。我们还探索了三种构建正负样本的策略和两种提取修正向量的方法，形成了多种方法变体。实验表明，内部激活修正方法显著提升了VLMs的安全性，在SafeBench、Safe-Unsafe、Unsafe和MM-SafetyBench上的攻击成功率分别平均降低了48.94%、34.34%、43.92%和52.98%，同时对模型的有用性影响极小。

> Vision-language models (VLMs) demonstrate strong multimodal capabilities but have been found to be more susceptible to generating harmful content compared to their backbone large language models (LLMs). Our investigation reveals that the integration of images significantly shifts the model's internal activations during the forward pass, diverging from those triggered by textual input. Moreover, the safety alignments of LLMs embedded within VLMs are not sufficiently robust to handle the activations discrepancies, making the models vulnerable to even the simplest jailbreaking attacks. To address this issue, we propose an \textbf{internal activation revision} approach that efficiently revises activations during generation, steering the model toward safer outputs. Our framework incorporates revisions at both the layer and head levels, offering control over the model's generation at varying levels of granularity. In addition, we explore three strategies for constructing positive and negative samples and two approaches for extracting revision vectors, resulting in different variants of our method. Comprehensive experiments demonstrate that the internal activation revision method significantly improves the safety of widely used VLMs, reducing attack success rates by an average of 48.94\%, 34.34\%, 43.92\%, and 52.98\% on SafeBench, Safe-Unsafe, Unsafe, and MM-SafetyBench, respectively, while minimally impacting model helpfulness.

[Arxiv](https://arxiv.org/abs/2501.16378)