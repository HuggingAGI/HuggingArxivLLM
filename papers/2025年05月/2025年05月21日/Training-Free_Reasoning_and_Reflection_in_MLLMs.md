# 多语言大规模语言模型中的无训练推理与反思

发布时间：2025年05月21日

`LLM应用` `多模态` `人工智能`

> Training-Free Reasoning and Reflection in MLLMs

# 摘要

> 近期，推理大型语言模型（如DeepSeek-R1和OpenAI-o1）通过强化学习展示了强大的推理能力。然而，将这些能力扩展到多模态大型语言模型（MLLMs）面临两大挑战：高昂的再训练成本和高质量多模态推理数据集的稀缺性。为此，我们提出了FRANK模型——一种无需训练、与r1类似的MLLM，它赋予现成的MLLM推理和反思能力，无需任何梯度更新或额外监督。

我们的核心思路是将感知与推理在MLLM的解码器层中解耦。研究发现，浅层解码器层更关注视觉令牌，而深层解码器层则专注于文本语义。这一发现启发我们提出了一种分层权重合并方法，将视觉预训练的MLLM与专门用于推理的LLM相结合。我们还设计了一种基于Taylor展开的分层闭合形式融合机制，将推理能力融入深层解码器层，同时保留浅层解码器层的视觉定位能力。

实验结果表明，FRANK模型在多模态推理任务中表现出色。在MMMU基准测试中，FRANK-38B模型达到了69.2%的准确率，比最强基线InternVL2.5-38B高出+5.3%，甚至超越了专有的GPT-4o模型。更多详情请访问我们的项目主页：http://iip.whu.edu.cn/frank/index.html

> Recent advances in Reasoning LLMs (e.g., DeepSeek-R1 and OpenAI-o1) have showcased impressive reasoning capabilities via reinforcement learning. However, extending these capabilities to Multimodal LLMs (MLLMs) is hampered by the prohibitive costs of retraining and the scarcity of high-quality, verifiable multimodal reasoning datasets. This paper introduces FRANK Model, a training-FRee ANd r1-liKe MLLM that imbues off-the-shelf MLLMs with reasoning and reflection abilities, without any gradient updates or extra supervision. Our key insight is to decouple perception and reasoning across MLLM decoder layers. Specifically, we observe that compared to the deeper decoder layers, the shallow decoder layers allocate more attention to visual tokens, while the deeper decoder layers concentrate on textual semantics. This observation motivates a hierarchical weight merging approach that combines a visual-pretrained MLLM with a reasoning-specialized LLM. To this end, we propose a layer-wise, Taylor-derived closed-form fusion mechanism that integrates reasoning capacity into deep decoder layers while preserving visual grounding in shallow decoder layers. Extensive experiments on challenging multimodal reasoning benchmarks demonstrate the effectiveness of our approach. On the MMMU benchmark, our model FRANK-38B achieves an accuracy of 69.2, outperforming the strongest baseline InternVL2.5-38B by +5.3, and even surpasses the proprietary GPT-4o model. Our project homepage is at: http://iip.whu.edu.cn/frank/index.html

[Arxiv](https://arxiv.org/abs/2505.16151)