# # 摘要
并非所有的思考都同等重要：利用多轮强化学习优化LLM推理效率

发布时间：2025年05月17日

`LLM应用` `人工智能` `优化方法`

> Not All Thoughts are Generated Equal: Efficient LLM Reasoning via Multi-Turn Reinforcement Learning

# 摘要

> 压缩大型语言模型（LLMs）中的长链式思考（CoT）是提升LLMs推理效率的新兴策略。然而，现有研究对长CoT中的所有思考进行同等压缩，限制了更简洁有效的推理。我们通过自动长CoT分块和蒙特卡洛展开，研究不同思考的重要性，评估其在推理中的有效性和效率。基于此，我们提出了一种有理论边界的新指标，用于综合衡量不同思考的有效性和效率。我们还提出了Long⊗Short，一个高效推理框架，使两个LLMs协同解决问题：一个长链式思考的LLM更有效地生成重要思考，另一个短链式思考的LLM高效生成剩余思考。具体来说，我们合成少量冷启动数据，分别对LLMs进行长链式和短链式推理风格的微调。此外，我们提出了一种协同导向的多轮强化学习方法，重点在于模型自我进化以及长链式和短链式LLM之间的协作。实验结果表明，我们的方法使Qwen2.5-7B和Llama3.1-8B在MATH500、AIME24/25、AMC23和GPQA Diamond基准测试中，与DeepSeek-R1-Distill-Qwen-7B和DeepSeek-R1-Distill-Llama-8B相比，性能相当，同时将标记长度减少了80%以上。我们的数据和代码可在https://github.com/yasNing/Long-otimes-Short/获取。

> Compressing long chain-of-thought (CoT) from large language models (LLMs) is an emerging strategy to improve the reasoning efficiency of LLMs. Despite its promising benefits, existing studies equally compress all thoughts within a long CoT, hindering more concise and effective reasoning. To this end, we first investigate the importance of different thoughts by examining their effectiveness and efficiency in contributing to reasoning through automatic long CoT chunking and Monte Carlo rollouts. Building upon the insights, we propose a theoretically bounded metric to jointly measure the effectiveness and efficiency of different thoughts. We then propose Long$\otimes$Short, an efficient reasoning framework that enables two LLMs to collaboratively solve the problem: a long-thought LLM for more effectively generating important thoughts, while a short-thought LLM for efficiently generating remaining thoughts. Specifically, we begin by synthesizing a small amount of cold-start data to fine-tune LLMs for long-thought and short-thought reasoning styles, respectively. Furthermore, we propose a synergizing-oriented multi-turn reinforcement learning, focusing on the model self-evolution and collaboration between long-thought and short-thought LLMs. Experimental results show that our method enables Qwen2.5-7B and Llama3.1-8B to achieve comparable performance compared to DeepSeek-R1-Distill-Qwen-7B and DeepSeek-R1-Distill-Llama-8B, while reducing token length by over 80% across the MATH500, AIME24/25, AMC23, and GPQA Diamond benchmarks. Our data and code are available at https://github.com/yasNing/Long-otimes-Short/.

[Arxiv](https://arxiv.org/abs/2505.11827)