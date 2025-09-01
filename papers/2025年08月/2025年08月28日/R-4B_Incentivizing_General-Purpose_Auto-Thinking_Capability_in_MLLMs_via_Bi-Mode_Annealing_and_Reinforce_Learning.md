# R-4B：借助双模式退火与强化学习激发多模态大型语言模型（MLLMs）的通用自动思考能力

发布时间：2025年08月28日

`LLM应用` `基础理论`

> R-4B: Incentivizing General-Purpose Auto-Thinking Capability in MLLMs via Bi-Mode Annealing and Reinforce Learning

# 摘要

> 具备逐步思考能力的多模态大型语言模型（MLLMs）在复杂推理任务中已展现出惊人性能。但对于无需复杂推理就能解决的简单问题，这种思考过程反而显得冗余。为解决这一效率问题，我们提出自动思考型多模态大型语言模型R-4B，它能根据问题复杂度自适应决定是否需要启动思考。R-4B的核心思路是借助双模式退火技术赋予模型思考与非思考双能力，并通过双模式策略优化（BPO）提升模型判断是否启动思考过程的准确性。具体来说，我们首先在精心构建的多主题数据集上训练模型，该数据集同时包含思考模式和非思考模式的样本。随后，模型在改进的GRPO框架下进行第二阶段训练，在此过程中，策略模型需为每个输入查询生成两种模式的响应。实验结果显示，R-4B在25项极具挑战性的基准测试中均实现了最先进性能：在大多数任务中，它的表现优于Qwen2.5-VL-7B；而在推理密集型基准测试中，它以更低的计算成本实现了与Kimi-VL-A3B-Thinking-2506（16B）等更大模型相当的性能。

> Multimodal Large Language Models (MLLMs) equipped with step-by-step thinking capabilities have demonstrated remarkable performance on complex reasoning problems. However, this thinking process is redundant for simple problems solvable without complex reasoning. To address this inefficiency, we propose R-4B, an auto-thinking MLLM, which can adaptively decide when to think based on problem complexity. The central idea of R-4B is to empower the model with both thinking and non-thinking capabilities using bi-mode annealing, and apply Bi-mode Policy Optimization~(BPO) to improve the model's accuracy in determining whether to activate the thinking process. Specifically, we first train the model on a carefully curated dataset spanning various topics, which contains samples from both thinking and non-thinking modes. Then it undergoes a second phase of training under an improved GRPO framework, where the policy model is forced to generate responses from both modes for each input query. Experimental results show that R-4B achieves state-of-the-art performance across 25 challenging benchmarks. It outperforms Qwen2.5-VL-7B in most tasks and achieves performance comparable to larger models such as Kimi-VL-A3B-Thinking-2506 (16B) on reasoning-intensive benchmarks with lower computational cost.

[Arxiv](https://arxiv.org/abs/2508.21113)