# 大语言模型中的灾难性遗忘现象：跨语言任务的比较分析

发布时间：2025年04月01日

`LLM理论` `自然语言理解`

> Catastrophic Forgetting in LLMs: A Comparative Analysis Across Language Tasks

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域取得了显著进展，特别是在自然语言理解（NLU）任务方面。随着我们迈向一个基于LLM的智能体自主处理专业任务的未来世界，这些模型需要在不遗忘先前学习信息的情况下适应新任务——这一挑战被称为灾难性遗忘。本研究评估了不同规模的开源LLMs（特别是参数量低于100亿的模型）在GLUE基准中的关键NLU任务（包括SST-2、MRPC、CoLA和MNLI）上的持续微调表现。通过运用提示工程和任务特定调整，我们评估并比较了模型在学习新任务时保留先前知识的能力。我们的结果显示，Phi-3.5-mini等模型表现出最小的遗忘并保持强大的学习能力，使其非常适合持续学习环境。此外，Orca-2-7b和Qwen2.5-7B等模型在微调后也展现出出色的学习能力和整体性能。这项工作有助于理解LLMs中的灾难性遗忘现象，并强调了提示工程在优化持续学习场景下模型性能中的作用。


> Large Language Models (LLMs) have significantly advanced Natural Language Processing (NLP), particularly in Natural Language Understanding (NLU) tasks. As we progress toward an agentic world where LLM-based agents autonomously handle specialized tasks, it becomes crucial for these models to adapt to new tasks without forgetting previously learned information - a challenge known as catastrophic forgetting. This study evaluates the continual fine-tuning of various open-source LLMs with different parameter sizes (specifically models under 10 billion parameters) on key NLU tasks from the GLUE benchmark, including SST-2, MRPC, CoLA, and MNLI. By employing prompt engineering and task-specific adjustments, we assess and compare the models' abilities to retain prior knowledge while learning new tasks. Our results indicate that models such as Phi-3.5-mini exhibit minimal forgetting while maintaining strong learning capabilities, making them well-suited for continual learning environments. Additionally, models like Orca-2-7b and Qwen2.5-7B demonstrate impressive learning abilities and overall performance after fine-tuning. This work contributes to understanding catastrophic forgetting in LLMs and highlights prompting engineering to optimize model performance for continual learning scenarios.

[Arxiv](https://arxiv.org/abs/2504.01241)