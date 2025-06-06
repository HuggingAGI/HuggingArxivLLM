# 通过奖励优化的图像描述生成实现感知解耦，用于可扩展的多模态推理

发布时间：2025年06月04日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：近期，慢思考语言模型（如 OpenAI-o1 和 DeepSeek-R1）在复杂推理任务中展现了非凡的能力，通过模拟人类的反思性认知。然而，将这些能力扩展到多模态大型语言模型（MLLMs）仍然面临挑战，主要由于升级底层推理 LLM 时视觉语言对齐的高昂成本。一个直接的解决方案是将感知与推理分离，即将视觉输入转换为语言表示（如字幕），然后传递给强大的纯文本推理器。然而，这种分离引入了一个关键挑战：视觉提取器必须生成既忠实于图像又足够信息量以支持准确下游推理的描述。为了解决这一问题，我们提出了基于字幕奖励优化的推理对齐感知解耦（RACRO）——一种由推理引导的强化学习策略，旨在将提取器的字幕生成行为与推理目标对齐。通过基于奖励的优化来闭合感知-推理循环，RACRO显著提升了视觉定位并提取了推理优化的表示。在多模态数学和科学基准测试中的实验表明，所提出的 RACRO 方法实现了最先进的平均性能，同时具备卓越的扩展性和即插即用的适应性，可轻松适配更先进的推理 LLM，而无需进行昂贵的多模态重新对齐。
LLM应用` `人工智能` `认知科学`

> Perceptual Decoupling for Scalable Multi-modal Reasoning via Reward-Optimized Captioning

# 摘要

> 近期，慢思考语言模型（如 OpenAI-o1 和 DeepSeek-R1）在复杂推理任务中展现了非凡的能力，通过模拟人类的反思性认知。然而，将这些能力扩展到多模态大型语言模型（MLLMs）仍然面临挑战，主要由于升级底层推理 LLM 时视觉语言对齐的高昂成本。一个直接的解决方案是将感知与推理分离，即将视觉输入转换为语言表示（如字幕），然后传递给强大的纯文本推理器。然而，这种分离引入了一个关键挑战：视觉提取器必须生成既忠实于图像又足够信息量以支持准确下游推理的描述。为了解决这一问题，我们提出了基于字幕奖励优化的推理对齐感知解耦（RACRO）——一种由推理引导的强化学习策略，旨在将提取器的字幕生成行为与推理目标对齐。通过基于奖励的优化来闭合感知-推理循环，RACRO显著提升了视觉定位并提取了推理优化的表示。在多模态数学和科学基准测试中的实验表明，所提出的 RACRO 方法实现了最先进的平均性能，同时具备卓越的扩展性和即插即用的适应性，可轻松适配更先进的推理 LLM，而无需进行昂贵的多模态重新对齐。

> Recent advances in slow-thinking language models (e.g., OpenAI-o1 and DeepSeek-R1) have demonstrated remarkable abilities in complex reasoning tasks by emulating human-like reflective cognition. However, extending such capabilities to multi-modal large language models (MLLMs) remains challenging due to the high cost of retraining vision-language alignments when upgrading the underlying reasoner LLMs. A straightforward solution is to decouple perception from reasoning, i.e., converting visual inputs into language representations (e.g., captions) that are then passed to a powerful text-only reasoner. However, this decoupling introduces a critical challenge: the visual extractor must generate descriptions that are both faithful to the image and informative enough to support accurate downstream reasoning. To address this, we propose Reasoning-Aligned Perceptual Decoupling via Caption Reward Optimization (RACRO) - a reasoning-guided reinforcement learning strategy that aligns the extractor's captioning behavior with the reasoning objective. By closing the perception-reasoning loop via reward-based optimization, RACRO significantly enhances visual grounding and extracts reasoning-optimized representations. Experiments on multi-modal math and science benchmarks show that the proposed RACRO method achieves state-of-the-art average performance while enabling superior scalability and plug-and-play adaptation to more advanced reasoning LLMs without the necessity for costly multi-modal re-alignment.

[Arxiv](https://arxiv.org/abs/2506.04559)