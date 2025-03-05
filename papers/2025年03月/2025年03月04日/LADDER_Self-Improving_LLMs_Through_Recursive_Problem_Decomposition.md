# LADDER：通过递归分解实现LLMs的自我改进

发布时间：2025年03月04日

`LLM应用` `数学教育` `教育技术`

> LADDER: Self-Improving LLMs Through Recursive Problem Decomposition

# 摘要

> 我们提出了LADDER框架（通过自主难度驱动示例递归学习），它让大型语言模型能够通过递归生成并解决更简单的复杂问题变体，自主提升问题解决能力。与依赖人工策划数据集或人类反馈的传统方法不同，LADDER充分利用模型自身能力生成更简单的题目变体。我们在数学积分领域验证了LADDER的效果，将Llama 3.2 3B在大学水平问题上的准确率从1%提升到82%，并使Qwen2.5 7B Deepseek-R1 Distilled在MIT积分竞赛资格考试中达到73%的准确率。同时，我们引入了TTRL（测试时强化学习），在推理阶段对测试问题的变体进行强化学习。TTRL使Qwen2.5 7B Deepseek-R1 Distilled在MIT积分竞赛资格考试中达到了90%的准确率，超越了OpenAI o1的表现。这些结果表明，自我指导的战略学习可以在不依赖架构扩展或人工监督的情况下实现显著的能力提升。

> We introduce LADDER (Learning through Autonomous Difficulty-Driven Example Recursion), a framework which enables Large Language Models to autonomously improve their problem-solving capabilities through self-guided learning by recursively generating and solving progressively simpler variants of complex problems. Unlike prior approaches that require curated datasets or human feedback, LADDER leverages a model's own capabilities to generate easier question variants. We demonstrate LADDER's effectiveness in the subject of mathematical integration, improving Llama 3.2 3B's accuracy from 1% to 82% on undergraduate-level problems and enabling Qwen2.5 7B Deepseek-R1 Distilled to achieve 73% on the MIT Integration Bee qualifying examination. We also introduce TTRL (Test-Time Reinforcement Learning), where we perform reinforcement learning on variants of test problems at inference time. TTRL enables Qwen2.5 7B Deepseek-R1 Distilled to achieve a state-of-the-art score of 90% on the MIT Integration Bee qualifying examination, surpassing OpenAI o1's performance. These results show how self-directed strategic learning can achieve significant capability improvements without relying on architectural scaling or human supervision.

[Arxiv](https://arxiv.org/abs/2503.00735)