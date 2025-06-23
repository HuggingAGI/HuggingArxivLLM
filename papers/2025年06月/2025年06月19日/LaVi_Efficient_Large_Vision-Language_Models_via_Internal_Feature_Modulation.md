# LaVi：通过内部特征调制高效构建大型视觉-语言模型

发布时间：2025年06月19日

`LLM应用` `计算机视觉` `多模态`

> LaVi: Efficient Large Vision-Language Models via Internal Feature Modulation

# 摘要

> 尽管大型视觉语言模型（LVLMs）取得了显著进展，但现有方法仍存在根本性瓶颈：视觉语言整合效率低下。当前方法要么破坏模型结构，要么带来长上下文计算负担，极大限制了扩展性和效率。本文重新思考多模态整合方式，提出了一种全新的LVLM——LaVi。LaVi通过在大型语言模型（LLMs）内部进行特征调制，实现了视觉语言的无缝高效融合。与主流的依赖视觉令牌拼接的LVLM不同，LaVi通过引入一种轻量级自适应变换，绕过了长上下文扩展的需要。该方法通过将基于视觉条件的逐令牌增量注入层归一化的仿射参数中，整合视觉上下文。这种机制能够直接根据视觉输入对语言隐含状态进行调制，在保持LLM语言先验的同时，实现精准的视觉语言对齐，并大幅降低计算成本。在15个图像和视频基准测试中的广泛评估表明，LaVi不仅达到了最先进的多模态性能，还显著提升了效率。与LLaVA-OV-7B相比，LaVi将FLOPs减少了94.0%，推理速度提升了3.1倍，内存使用量减半——确立了LaVi作为实时多模态推理的可扩展和实用解决方案的地位。代码和模型即将发布。

> Despite the impressive advancements of Large Vision-Language Models (LVLMs), existing approaches suffer from a fundamental bottleneck: inefficient visual-language integration. Current methods either disrupt the model's inherent structure or introduce severe long-context computational burden, severely limiting scalability and efficiency. In this paper, we rethink multimodal integration and present LaVi, a novel LVLM that enables seamless and efficient vision-language fusion through internal feature modulation within the Large Language Models (LLMs). Unlike dominant LVLMs that rely on visual token concatenation, LaVi bypasses long-context expansion by introducing a lightweight and adaptive transformation, which incorporates visual context by injecting token-wise vision-conditioned deltas into the affine parameters of layer normalization. This mechanism directly modulates linguistic hidden states based on visual input, ensuring precise vision-language alignment while preserving the LLM's linguistic priors and drastically reducing computational costs. Extensive evaluations across 15 image and video benchmarks demonstrate that LaVi not only achieves state-of-the-art multimodal performance but also dramatically enhances efficiency. Compared to LLaVA-OV-7B, LaVi reduces FLOPs by 94.0%, improves inference speed by 3.1 times, and cuts memory usage in half - establishing LaVi as a scalable and practical solution for real-time multimodal reasoning. The code and models will be released soon.

[Arxiv](https://arxiv.org/abs/2506.16691)