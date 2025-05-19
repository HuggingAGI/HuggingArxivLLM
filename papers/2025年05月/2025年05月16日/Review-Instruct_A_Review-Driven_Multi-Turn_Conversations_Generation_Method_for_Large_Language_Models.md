# Review-Instruct：基于评论的多轮对话生成方法，专为大型语言模型设计。

发布时间：2025年05月16日

`LLM应用` `对话AI` `数据生成`

> Review-Instruct: A Review-Driven Multi-Turn Conversations Generation Method for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在对话 AI 中的应用受到单轮监督微调 (SFT) 数据的限制，这导致多轮对话中上下文连贯性不足。现有的多轮对话数据生成方法难以同时保证指令的多样性和质量。为了解决这一问题，我们提出了 Review-Instruct，一个通过迭代的 "Ask-Respond-Review" 过程合成多轮对话的新型框架，涉及三个角色：Candidate、多个 Reviewers 和 Chairman。该框架通过整合 Reviewer 的反馈来迭代优化指令，从而提高对话的多样性和难度。我们使用 Alpaca 数据集构建了一个多轮对话数据集，并对 LLaMA2-13B 模型进行了微调。在 MT-Bench、MMLU-Pro 和 Auto-Arena 上的评估显示了显著的改进，与基于 LLaMA2-13B 的先前最先进模型相比，在 MMLU-Pro 上绝对提升了 2.9%，在 MT-Bench 上提升了 2%。消融研究证实了 Review 阶段和使用多个 Reviewers 在提升指令多样性和难度方面的重要作用。我们的工作展示了基于评审、多智能体框架在大规模生成高质量对话数据方面的潜力。

> The effectiveness of large language models (LLMs) in conversational AI is hindered by their reliance on single-turn supervised fine-tuning (SFT) data, which limits contextual coherence in multi-turn dialogues. Existing methods for generating multi-turn dialogue data struggle to ensure both diversity and quality in instructions. To address this, we propose Review-Instruct, a novel framework that synthesizes multi-turn conversations through an iterative "Ask-Respond-Review" process involving three agent roles: a Candidate, multiple Reviewers, and a Chairman. The framework iteratively refines instructions by incorporating Reviewer feedback, enhancing dialogue diversity and difficulty. We construct a multi-turn dataset using the Alpaca dataset and fine-tune the LLaMA2-13B model. Evaluations on MT-Bench, MMLU-Pro, and Auto-Arena demonstrate significant improvements, achieving absolute gains of 2.9\% on MMLU-Pro and 2\% on MT-Bench compared to prior state-of-the-art models based on LLaMA2-13B. Ablation studies confirm the critical role of the Review stage and the use of multiple Reviewers in boosting instruction diversity and difficulty. Our work highlights the potential of review-driven, multi-agent frameworks for generating high-quality conversational data at scale.

[Arxiv](https://arxiv.org/abs/2505.11010)