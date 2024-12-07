# 语言模型中的自我改进：锐化机制

发布时间：2024年12月02日

`LLM理论` `语言建模` `人工智能`

> Self-Improvement in Language Models: The Sharpening Mechanism

# 摘要

> 近期语言建模领域的工作让语言模型自我改进成为可能，即模型能评估并优化自身生成的结果，在无外部反馈时达到更优性能。但这种自我改进无法创造模型中原本没有的信息，那我们为何期待它能提升能力呢？我们从“锐化”这一视角，对自我改进的能力提出新看法。鉴于语言模型在验证响应质量上往往比生成正确响应更出色，我们把自我改进定义为在后训练阶段用模型自身作验证器，以“锐化”模型，使其更倾向高质量序列，从而分摊生成优质序列时昂贵的推理时间计算成本。首先，我们引入一个新的锐化统计框架，学习者可借此通过样本访问来锐化预训练的基本策略，并确立基本限制。接着，我们分析了基于 SFT 和 RLHF 的两个常见的自我改进算法族。

> Recent work in language modeling has raised the possibility of self-improvement, where a language models evaluates and refines its own generations to achieve higher performance without external feedback. It is impossible for this self-improvement to create information that is not already in the model, so why should we expect that this will lead to improved capabilities? We offer a new perspective on the capabilities of self-improvement through a lens we refer to as sharpening. Motivated by the observation that language models are often better at verifying response quality than they are at generating correct responses, we formalize self-improvement as using the model itself as a verifier during post-training in order to ``sharpen'' the model to one placing large mass on high-quality sequences, thereby amortizing the expensive inference-time computation of generating good sequences. We begin by introducing a new statistical framework for sharpening in which the learner aims to sharpen a pre-trained base policy via sample access, and establish fundamental limits. Then we analyze two natural families of self-improvement algorithms based on SFT and RLHF.

[Arxiv](https://arxiv.org/abs/2412.01951)