# PlanMoGPT：通过流增强渐进式规划实现文本到动作合成

发布时间：2025年06月22日

`LLM应用` `动作生成`

> PlanMoGPT: Flow-Enhanced Progressive Planning for Text to Motion Synthesis

# 摘要

> 大型语言模型（LLMs）的突破性进展推动了多模态生成任务的突破性发展，但在文本到动作生成领域，基于LLM的方法与非LLM方法之间仍存在显著性能差距。我们发现，动作分词的粒度是这一领域的主要瓶颈：细粒度分词导致局部依赖问题，使LLMs过于强调短期连贯性而忽视全局语义对齐，而粗粒度分词则会牺牲动作细节。为解决这一问题，我们提出了PlanMoGPT，一个结合渐进式规划和流增强细粒度动作分词的LLM框架。

具体而言，我们的渐进式规划机制利用LLMs的自回归能力，从稀疏全局计划开始，逐步细化生成完整的动作序列。同时，我们的流增强分词器将下采样分辨率提高一倍，并将码本大小扩大八倍，从而在离散化过程中最大限度地减少细节损失，而流增强解码器则恢复动作的细微差别。在文本到动作基准测试中的大量实验表明，该方法实现了最先进的性能，长序列生成的FID分数从0.380降至0.141（提升63.8%），同时与现有方法相比，动作多样性提高了49.9%。这一框架成功解决了困扰当前非LLM方法的多样性-质量权衡问题，为文本到动作生成设立了新标准。

> Recent advances in large language models (LLMs) have enabled breakthroughs in many multimodal generation tasks, but a significant performance gap still exists in text-to-motion generation, where LLM-based methods lag far behind non-LLM methods. We identify the granularity of motion tokenization as a critical bottleneck: fine-grained tokenization induces local dependency issues, where LLMs overemphasize short-term coherence at the expense of global semantic alignment, while coarse-grained tokenization sacrifices motion details. To resolve this issue, we propose PlanMoGPT, an LLM-based framework integrating progressive planning and flow-enhanced fine-grained motion tokenization. First, our progressive planning mechanism leverages LLMs' autoregressive capabilities to hierarchically generate motion tokens by starting from sparse global plans and iteratively refining them into full sequences. Second, our flow-enhanced tokenizer doubles the downsampling resolution and expands the codebook size by eight times, minimizing detail loss during discretization, while a flow-enhanced decoder recovers motion nuances. Extensive experiments on text-to-motion benchmarks demonstrate that it achieves state-of-the-art performance, improving FID scores by 63.8% (from 0.380 to 0.141) on long-sequence generation while enhancing motion diversity by 49.9% compared to existing methods. The proposed framework successfully resolves the diversity-quality trade-off that plagues current non-LLM approaches, establishing new standards for text-to-motion generation.

[Arxiv](https://arxiv.org/abs/2506.17912)