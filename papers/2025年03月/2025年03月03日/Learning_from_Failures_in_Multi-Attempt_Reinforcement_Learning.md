# 多尝试强化学习中的失败经验学习

发布时间：2025年03月03日

`LLM应用` `对话系统`

> Learning from Failures in Multi-Attempt Reinforcement Learning

# 摘要

> 研究表明，强化学习（RL）在大型语言模型（LLMs）中的应用，以DeepSeek R1为例，证明即使是简单的问答任务也能显著提升模型的推理能力。本研究将这一方法扩展至多轮尝试任务，模型在多次尝试中根据反馈优化回答，从而提高搜索效率。实验结果显示，小型LLM在多轮尝试任务下表现更优，数学基准测试中准确率从1次尝试的45.6%提升至2次尝试的52.5%。相比之下，标准单轮任务下，模型仅表现出微弱改进。这表明，多轮尝试任务不仅提升了模型性能，还增强了其根据反馈优化回答的能力。完整代码可在GitHub上获取：https://github.com/DualityRL/multi-attempt

> Recent advancements in reinforcement learning (RL) for large language models (LLMs), exemplified by DeepSeek R1, have shown that even a simple question-answering task can substantially improve an LLM's reasoning capabilities. In this work, we extend this approach by modifying the task into a multi-attempt setting. Instead of generating a single response per question, the model is given multiple attempts, with feedback provided after incorrect responses. The multi-attempt task encourages the model to refine its previous attempts and improve search efficiency. Experimental results show that even a small LLM trained on a multi-attempt task achieves significantly higher accuracy when evaluated with more attempts, improving from 45.6% with 1 attempt to 52.5% with 2 attempts on the math benchmark. In contrast, the same LLM trained on a standard single-turn task exhibits only a marginal improvement, increasing from 42.3% to 43.2% when given more attempts during evaluation. The results indicate that, compared to the standard single-turn task, an LLM trained on a multi-attempt task achieves slightly better performance on math benchmarks while also learning to refine its responses more effectively based on user feedback. Full code is available at https://github.com/DualityRL/multi-attempt

[Arxiv](https://arxiv.org/abs/2503.04808)