# 在多轮对话中测量语言模型的阿谀奉承程度

发布时间：2025年05月28日

`LLM应用` `对话系统`

> Measuring Sycophancy of Language Models in Multi-turn Dialogues

# 摘要

> 大型语言模型（LLMs）本应提供有益且无害的回应，但它们常常表现出逢迎行为——即不论事实准确性或伦理合理性，一味迎合用户观点。此前研究主要关注单轮对话中的事实准确性，忽视了现实交互的复杂性。本研究推出SYCON Bench，一个用于评估多轮、开放形式对话场景下逢迎行为的新基准。我们的基准测试通过两个维度衡量模型表现：一是模型对用户观点的快速迎合程度（翻转回合），二是模型在持续用户压力下立场转变的频率（翻转次数）。将SYCON Bench应用于涵盖三个现实场景的17种LLMs后，我们发现逢迎行为仍然是普遍存在的失效模式。分析表明，对齐调优会加剧逢迎行为，而模型扩展和推理优化则能增强模型抵御不良用户观点的能力。推理模型通常优于指令微调模型，但当它们过度侧重于逻辑阐述而非直接回应用户潜在信念时，往往会失败。最后，我们评估了四种额外的提示策略，并证明在辩论场景中采用第三人称视角可将逢迎行为减少高达63.8%。我们已在https://github.com/JiseungHong/SYCON-Bench公开了代码和数据。

> Large Language Models (LLMs) are expected to provide helpful and harmless responses, yet they often exhibit sycophancy--conforming to user beliefs regardless of factual accuracy or ethical soundness. Prior research on sycophancy has primarily focused on single-turn factual correctness, overlooking the dynamics of real-world interactions. In this work, we introduce SYCON Bench, a novel benchmark for evaluating sycophantic behavior in multi-turn, free-form conversational settings. Our benchmark measures how quickly a model conforms to the user (Turn of Flip) and how frequently it shifts its stance under sustained user pressure (Number of Flip). Applying SYCON Bench to 17 LLMs across three real-world scenarios, we find that sycophancy remains a prevalent failure mode. Our analysis shows that alignment tuning amplifies sycophantic behavior, whereas model scaling and reasoning optimization strengthen the model's ability to resist undesirable user views. Reasoning models generally outperform instruction-tuned models but often fail when they over-index on logical exposition instead of directly addressing the user's underlying beliefs. Finally, we evaluate four additional prompting strategies and demonstrate that adopting a third-person perspective reduces sycophancy by up to 63.8% in debate scenario. We release our code and data at https://github.com/JiseungHong/SYCON-Bench.

[Arxiv](https://arxiv.org/abs/2505.23840)