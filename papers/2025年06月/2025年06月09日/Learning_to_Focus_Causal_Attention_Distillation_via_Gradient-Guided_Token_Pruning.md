# 学习专注：通过梯度引导分词蒸馏的因果注意力机制

发布时间：2025年06月09日

`LLM理论` `人工智能`

> Learning to Focus: Causal Attention Distillation via Gradient-Guided Token Pruning

# 摘要

> 大型语言模型（LLMs）的上下文理解能力虽有显著提升，但在长上下文推理和生成中关注关键信息的能力仍显不足。我们的初步实验发现，某些分心模式会在推理过程中误导模型注意力，而移除这些模式能显著提高推理准确性和生成质量。这一现象源于训练数据中的虚假关联，这些虚假关联阻碍了模型对真实因果指令-响应关系的推断能力。这可能导致冗余推理过程，不仅增加推理开销，还可能生成错误或次优的响应。为解决这一问题，我们提出了一种名为学习专注（LeaF）的两阶段框架，通过基于干预的推理分离混杂因素。第一阶段，LeaF借助与先进教师模型的梯度比较，基于训练语料库中的因果关系自动识别混杂令牌。第二阶段，它在蒸馏过程中剪枝这些令牌以实施干预，使学生的注意力与教师对关键上下文令牌的关注分布保持一致。实验结果表明，LeaF不仅在数学推理和代码生成基准上实现了性能提升，还在推理过程中有效抑制了对混杂令牌的关注，生成了更具解释性和可靠性的推理模型。

> Large language models (LLMs) have demonstrated significant improvements in contextual understanding. However, their ability to attend to truly critical information during long-context reasoning and generation still falls behind the pace. Specifically, our preliminary experiments reveal that certain distracting patterns can misdirect the model's attention during inference, and removing these patterns substantially improves reasoning accuracy and generation quality. We attribute this phenomenon to spurious correlations in the training data, which obstruct the model's capacity to infer authentic causal instruction-response relationships. This phenomenon may induce redundant reasoning processes, potentially resulting in significant inference overhead and, more critically, the generation of erroneous or suboptimal responses. To mitigate this, we introduce a two-stage framework called Learning to Focus (LeaF) leveraging intervention-based inference to disentangle confounding factors. In the first stage, LeaF employs gradient-based comparisons with an advanced teacher to automatically identify confounding tokens based on causal relationships in the training corpus. Then, in the second stage, it prunes these tokens during distillation to enact intervention, aligning the student's attention with the teacher's focus distribution on truly critical context tokens. Experimental results demonstrate that LeaF not only achieves an absolute improvement in various mathematical reasoning and code generation benchmarks but also effectively suppresses attention to confounding tokens during inference, yielding a more interpretable and reliable reasoning model.

[Arxiv](https://arxiv.org/abs/2506.07851)