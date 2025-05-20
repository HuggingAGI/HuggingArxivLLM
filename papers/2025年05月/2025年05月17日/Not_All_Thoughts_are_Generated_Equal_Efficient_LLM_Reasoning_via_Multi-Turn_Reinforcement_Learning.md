# 并非所有想法都生而平等：多轮强化学习助力高效LLM推理

发布时间：2025年05月17日

`LLM应用` `大型语言模型` `推理系统`

> Not All Thoughts are Generated Equal: Efficient LLM Reasoning via Multi-Turn Reinforcement Learning

# 摘要

> 压缩大型语言模型 (LLMs) 中的长链式思考 (CoT) 是一种提升推理效率的新兴策略。然而，现有研究对长 CoT 中的所有思考进行等量压缩，这限制了推理的简洁性和有效性。为解决这一问题，我们首先通过自动长 CoT 分块和蒙特卡洛展开，分析不同思考在推理中的有效性和效率，以此评估其重要性。基于这些洞察，我们提出了一种理论有界的指标，用于综合衡量不同思考的有效性和效率。随后，我们提出了 Long$\otimes$Short，一个高效推理框架，使两个 LLM 协作解决问题：一个擅长生成重要思考的长思维 LLM，以及一个高效生成剩余思考的短思维 LLM。具体而言，我们首先合成少量冷启动数据，分别对 LLMs 进行长思维和短思维推理风格的微调。此外，我们提出了一种协同导向的多轮强化学习方法，专注于模型自我进化以及长思维和短思维 LLM 之间的协作。实验结果显示，我们的方法使 Qwen2.5-7B 和 Llama3.1-8B 在 MATH500、AIME24/25、AMC23 和 GPQA Diamond 基准测试中的令牌长度减少了 80%以上，同时达到与 DeepSeek-R1-Distill-Qwen-7B 和 DeepSeek-R1-Distill-Llama-8B 相当的性能。我们的数据和代码可在 https://github.com/yasNing/Long-otimes-Short/ 获取。

> Compressing long chain-of-thought (CoT) from large language models (LLMs) is an emerging strategy to improve the reasoning efficiency of LLMs. Despite its promising benefits, existing studies equally compress all thoughts within a long CoT, hindering more concise and effective reasoning. To this end, we first investigate the importance of different thoughts by examining their effectiveness and efficiency in contributing to reasoning through automatic long CoT chunking and Monte Carlo rollouts. Building upon the insights, we propose a theoretically bounded metric to jointly measure the effectiveness and efficiency of different thoughts. We then propose Long$\otimes$Short, an efficient reasoning framework that enables two LLMs to collaboratively solve the problem: a long-thought LLM for more effectively generating important thoughts, while a short-thought LLM for efficiently generating remaining thoughts. Specifically, we begin by synthesizing a small amount of cold-start data to fine-tune LLMs for long-thought and short-thought reasoning styles, respectively. Furthermore, we propose a synergizing-oriented multi-turn reinforcement learning, focusing on the model self-evolution and collaboration between long-thought and short-thought LLMs. Experimental results show that our method enables Qwen2.5-7B and Llama3.1-8B to achieve comparable performance compared to DeepSeek-R1-Distill-Qwen-7B and DeepSeek-R1-Distill-Llama-8B, while reducing token length by over 80% across the MATH500, AIME24/25, AMC23, and GPQA Diamond benchmarks. Our data and code are available at https://github.com/yasNing/Long-otimes-Short/.

[Arxiv](https://arxiv.org/abs/2505.11827)