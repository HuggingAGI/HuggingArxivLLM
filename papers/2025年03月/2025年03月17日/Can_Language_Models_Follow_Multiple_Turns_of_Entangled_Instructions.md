# 语言模型能否应对多轮相互交织的指令？

发布时间：2025年03月17日

`LLM应用

理由：这篇论文研究了大型语言模型在多轮指令处理中的能力，分析了不同任务中的表现和权衡关系。研究集中在LLM在实际任务中的应用和性能评估，属于LLM应用的范畴。` `人工智能`

> Can Language Models Follow Multiple Turns of Entangled Instructions?

# 摘要

> 尽管大型语言模型（LLMs）的指令遵循能力已有显著提升，但处理多个相互纠缠或冲突的指令仍是一项重大挑战。现实场景中，保密隐私、个人偏好和优先级等需求要求模型在多轮指令交汇或冲突时具备整合信息、权衡目标的复杂能力。本研究系统性地考察了LLMs在多轮指令处理中的能力，涵盖三个难度级别：信息检索、跨轮推理与冲突解决。我们通过人工在环方法构建了包含约1.1K高质量对话的MultiTurnInstruct数据集，并归纳出九种能力类别，包括静态与动态、推理和多任务处理等。研究发现，不同能力之间存在显著的权衡关系。GPT模型虽在记忆力上表现优异，但在需要选择性 withholding 信息的隐私保护任务中效果下降。更大模型的推理能力更强，但解决冲突指令仍显吃力。值得注意的是，这些性能差距并非仅由信息丢失导致，尽管模型在记忆力任务中BLEU分数优异，但其注意力机制难以有效整合多个相关指令。这些发现为提升复杂现实任务中的多轮指令处理能力指明了方向。

> Despite significant achievements in improving the instruction-following capabilities of large language models (LLMs), the ability to process multiple potentially entangled or conflicting instructions remains a considerable challenge. Real-world scenarios often require consistency across multiple instructions over time, such as secret privacy, personal preferences, and prioritization, which demand sophisticated abilities to integrate multiple turns and carefully balance competing objectives when instructions intersect or conflict. This work presents a systematic investigation of LLMs' capabilities in handling multiple turns of instructions, covering three levels of difficulty: (1) retrieving information from instructions, (2) tracking and reasoning across turns, and (3) resolving conflicts among instructions. We construct MultiTurnInstruct with around 1.1K high-quality multi-turn conversations through the human-in-the-loop approach and result in nine capability categories, including statics and dynamics, reasoning, and multitasking. Our finding reveals an intriguing trade-off between different capabilities. While GPT models demonstrate superior memorization, they show reduced effectiveness in privacy-protection tasks requiring selective information withholding. Larger models exhibit stronger reasoning capabilities but still struggle with resolving conflicting instructions. Importantly, these performance gaps cannot be attributed solely to information loss, as models demonstrate strong BLEU scores on memorization tasks but their attention mechanisms fail to integrate multiple related instructions effectively. These findings highlight critical areas for improvement in complex real-world tasks involving multi-turn instructions.

[Arxiv](https://arxiv.org/abs/2503.13222)