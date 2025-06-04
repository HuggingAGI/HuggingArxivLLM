# 先扩展后推理：通过提前层插值提升大型语言模型的事实准确性

发布时间：2025年06月03日

`LLM理论

摘要讨论了大型语言模型（LLMs）中的“幻觉”问题，并提出了一种新的方法（PLI）来解决这一问题。PLI方法专注于模型的内在信息处理机制，通过数学插值在模型的不同层之间构建新的层，从而改进模型的事实一致性。该方法不需要额外的训练，并且在实验中表现出显著的效果。论文还分析了该方法与模型内部机制的关系，进一步揭示了模型的工作原理。因此，这篇论文主要贡献在于对LLM内在机制的理解和改进，属于LLM理论的范畴。` `信息检索` `问答系统`

> Expanding before Inferring: Enhancing Factuality in Large Language Models through Premature Layers Interpolation

# 摘要

> 大型语言模型（LLMs）在文本理解和生成方面表现出色，但“幻觉”问题仍是其一大挑战——即模型常产生事实不一致的输出。现有方法如检索增强和推理时校正，多从输入或输出层面入手，往往忽视了内在信息精炼过程及过早层的作用。而基于对齐和微调的方法又因资源消耗过大而不具优势。本文提出PLI（Premature Layers Interpolation），一种无需训练、即插即用的创新方法，专注于提升事实性表现。PLI通过数学插值在相邻层间构建过早层并将其插入模型，有效缓解幻觉问题。受稳定扩散和采样步骤启发，PLI扩展了LLMs中信息处理和传输的深度，显著提升了事实连贯性。实验结果表明，在四个公开数据集上，PLI不仅有效降低了幻觉，还在大多数情况下超越现有基线。进一步分析发现，层插值的成功与LLMs的内部机制密切相关。为促进研究可重复性，我们承诺将在论文被接受后公开代码和数据。

> Large Language Models (LLMs) demonstrate remarkable capabilities in text understanding and generation. However, their tendency to produce factually inconsistent outputs, commonly referred to as ''hallucinations'', remains a critical challenge. Existing approaches, such as retrieval-based and inference-time correction methods, primarily address this issue at the input or output level, often overlooking the intrinsic information refinement process and the role of premature layers. Meanwhile, alignment- and fine-tuning-based methods are resource-intensive. In this paper, we propose PLI (Premature Layers Interpolation), a novel, training-free, and plug-and-play intervention designed to enhance factuality. PLI mitigates hallucinations by inserting premature layers formed through mathematical interpolation with adjacent layers. Inspired by stable diffusion and sampling steps, PLI extends the depth of information processing and transmission in LLMs, improving factual coherence. Experiments on four publicly available datasets demonstrate that PLI effectively reduces hallucinations while outperforming existing baselines in most cases. Further analysis suggests that the success of layer interpolation is closely linked to LLMs' internal mechanisms. To promote reproducibility, we will release our code and data upon acceptance.

[Arxiv](https://arxiv.org/abs/2506.02973)