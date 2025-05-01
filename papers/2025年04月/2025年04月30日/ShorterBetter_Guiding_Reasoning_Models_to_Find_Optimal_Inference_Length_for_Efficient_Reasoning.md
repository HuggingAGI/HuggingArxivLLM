# ShorterBetter：引导推理模型寻找最优推理长度，实现高效推理

发布时间：2025年04月30日

`LLM应用` `推理模型` `优化方法`

> ShorterBetter: Guiding Reasoning Models to Find Optimal Inference Length for Efficient Reasoning

# 摘要

> 推理模型如 OpenAI o3 和 DeepSeek-R1 通过延长的思维链（CoT）提示，在需要大量推理的任务中表现出色。然而，尽管较长的推理轨迹有助于更全面地探索复杂问题的解决方案路径，但研究者发现这些模型经常“过度思考”，导致推理效率低下。本文中，我们引入了 ShorterBetter，这是一种简单而有效的强化学习方法，使推理语言模型能够在无人干预的情况下发现自身最优的 CoT 长度。通过为每个问题采样多个输出，并将样本最优长度（SOL）定义为所有输出中最短的正确回答，我们的方法动态引导模型向最优推理长度靠近。应用于 DeepSeek-Distill-Qwen-1.5B 模型，ShorterBetter 在保持准确性的前提下，使推理任务（包括领域内和领域外）的输出长度减少了高达 80%。我们的分析表明，过长的推理轨迹往往反映了推理方向的迷失，因此推理模型生成的延长 CoT 具有高度可压缩性。

> Reasoning models such as OpenAI o3 and DeepSeek-R1 have demonstrated strong performance on reasoning-intensive tasks through extended Chain-of-Thought (CoT) prompting. While longer reasoning traces can facilitate a more thorough exploration of solution paths for complex problems, researchers have observed that these models often "overthink", leading to inefficient inference. In this paper, we introduce ShorterBetter, a simple yet effective reinforcement learning methed that enables reasoning language models to discover their own optimal CoT lengths without human intervention. By sampling multiple outputs per problem and defining the Sample Optimal Length (SOL) as the shortest correct response among all the outputs, our method dynamically guides the model toward optimal inference lengths. Applied to the DeepSeek-Distill-Qwen-1.5B model, ShorterBetter achieves up to an 80% reduction in output length on both in-domain and out-of-domain reasoning tasks while maintaining accuracy. Our analysis shows that overly long reasoning traces often reflect loss of reasoning direction, and thus suggests that the extended CoT produced by reasoning models is highly compressible.

[Arxiv](https://arxiv.org/abs/2504.21370)