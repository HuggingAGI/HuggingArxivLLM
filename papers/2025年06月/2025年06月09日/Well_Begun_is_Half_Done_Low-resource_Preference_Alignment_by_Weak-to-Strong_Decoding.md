# # 好的开始是成功的一半：通过从弱到强的解码实现资源受限条件下的偏好对齐

发布时间：2025年06月09日

`LLM理论` `人工智能` `人机交互`

> Well Begun is Half Done: Low-resource Preference Alignment by Weak-to-Strong Decoding

# 摘要

> 大型语言模型（LLMs）需要与人类偏好保持一致，以避免生成冒犯性、虚假或无意义的内容。尽管资源有限的LLM对齐方法最近变得流行，但如何在获得高质量且一致的内容方面仍面临挑战。基于观察到生成一致响应的难度主要集中在解码的初期阶段，我们提出了一种名为弱到强解码（WSD）的新框架，通过一个小规模的对齐模型的引导来增强基础模型的对齐能力。

具体而言，小模型首先起草良好对齐的开头部分，随后由大型基础模型在精心设计的自动切换机制控制下继续生成其余内容。我们还收集了一个新的数据集GenerAlign，用于微调一个小型的Pilot-3B作为起草模型。实验结果表明，该模型在WSD框架下有效增强了不同的基础模型，使其在所有基线方法中表现最佳，同时避免了下游任务中的性能下降，即所谓的对齐税。

我们进一步进行了大量实验，以评估不同设置和时间效率的影响，并深入分析了WSD的内在机制。


> Large Language Models (LLMs) require alignment with human preferences to avoid generating offensive, false, or meaningless content. Recently, low-resource methods for LLM alignment have been popular, while still facing challenges in obtaining both high-quality and aligned content. Motivated by the observation that the difficulty of generating aligned responses is concentrated at the beginning of decoding, we propose a novel framework, Weak-to-Strong Decoding (WSD), to enhance the alignment ability of base models by the guidance of a small aligned model. The small model first drafts well-aligned beginnings, followed by the large base model to continue the rest, controlled by a well-designed auto-switch mechanism. We also collect a new dataset, GenerAlign, to fine-tune a small-sized Pilot-3B as the draft model, which effectively enhances different base models under the WSD framework to outperform all baseline methods, while avoiding degradation on downstream tasks, termed as the alignment tax. Extensive experiments are further conducted to examine the impact of different settings and time efficiency, as well as analyses on the intrinsic mechanisms of WSD in depth.

[Arxiv](https://arxiv.org/abs/2506.07434)