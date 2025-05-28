# 思考者：掌握快速与深度思考的艺术

发布时间：2025年05月27日

`LLM应用`

> Thinker: Learning to Think Fast and Slow

# 摘要

> 近期研究表明，通过强化学习提升大型语言模型在数学和编码等领域的问答任务推理能力。得益于长上下文长度，LLMs 可能学会执行搜索，正如在 DeepSeek R1 中观察到的自我修正行为所示。然而，这种搜索行为通常不够精准且缺乏信心，导致冗长重复的回答，凸显了直觉和验证方面的不足。受心理学中的双重过程理论启发，我们在问答任务中引入了一个简单的四阶段修改：快速思考，其中 LLM 必须在严格的令牌预算内作答；验证，模型评估其初始回答；慢速思考，它以更审慎的方式细化初始回答；以及总结，它将前一阶段的细化结果浓缩为精确步骤。我们的提议任务将 Qwen2.5-1.5B 的平均准确率从 24.9% 提升至 27.9%，并将 DeepSeek-R1-Qwen-1.5B 的准确率从 45.9% 提升至 49.8%。值得注意的是，仅 Qwen2.5-1.5B 的快速思考模式就达到了 26.8% 的准确率，使用少于 1000 个令牌，展示了显著的推理效率提升。这些发现表明，直觉和审慎推理是不同的、互补的系统，能够从针对性的训练中受益。

> Recent studies show that the reasoning capabilities of Large Language Models (LLMs) can be improved by applying Reinforcement Learning (RL) to question-answering (QA) tasks in areas such as math and coding. With a long context length, LLMs may learn to perform search, as indicated by the self-correction behavior observed in DeepSeek R1. However, this search behavior is often imprecise and lacks confidence, resulting in long, redundant responses and highlighting deficiencies in intuition and verification. Inspired by the Dual Process Theory in psychology, we introduce a simple modification to the QA task that includes four stages: Fast Thinking, where the LLM must answer within a strict token budget; Verification, where the model evaluates its initial response; Slow Thinking, where it refines the initial response with more deliberation; and Summarization, where it distills the refinement from the previous stage into precise steps. Our proposed task improves average accuracy from 24.9% to 27.9% for Qwen2.5-1.5B, and from 45.9% to 49.8% for DeepSeek-R1-Qwen-1.5B. Notably, for Qwen2.5-1.5B, the Fast Thinking mode alone achieves 26.8% accuracy using fewer than 1000 tokens, demonstrating substantial inference efficiency gains. These findings suggest that intuition and deliberative reasoning are distinct, complementary systems benefiting from targeted training.

[Arxiv](https://arxiv.org/abs/2505.21097)