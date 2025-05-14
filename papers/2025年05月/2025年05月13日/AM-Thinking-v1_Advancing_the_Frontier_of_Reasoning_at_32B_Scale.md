# # AM-Thinking-v1：在320亿参数规模上推动推理前沿

发布时间：2025年05月13日

`LLM应用

理由：这篇论文介绍了AM-Thinking-v1语言模型的设计、训练方法及其在多个评测中的表现，展示了其在数学和编码推理能力上的应用。论文的重点在于模型的应用性能和实际部署，符合LLM应用的分类标准。`

> AM-Thinking-v1: Advancing the Frontier of Reasoning at 32B Scale

# 摘要

> 我们很高兴推出 AM-Thinking-v1——一款拥有 320 亿参数的密集型语言模型，它不仅推动了推理能力的前沿发展，更体现了开源创新的协作精神。在 AIME 2024、AIME 2025 和 LiveCodeBench 等评测中，AM-Thinking-v1 以 85.3、74.4 和 70.3 的优异成绩，超越了 DeepSeek-R1，与 Qwen3-235B-A22B 和 Seed1.5-Thinking 等顶尖专家混合模型 (MoE) 平分秋色，彰显了开源模型中同类规模下的顶尖数学和编码实力。
    AM-Thinking-v1 基于开源的 Qwen2.5-32B 基础模型和公开查询数据打造，通过结合监督微调和强化学习的精良后训练管道，实现了卓越的推理能力。本研究不仅证明了开源社区在 320 亿参数规模下同样能够实现高性能，更展现了这一规模在部署和微调中的实际应用价值。我们希望 AM-Thinking-v1 能够激发更多协作，推动中型规模模型的推理边界，同时让创新始终以可访问性为核心。目前，我们已在 \href{https://huggingface.co/a-m-team/AM-Thinking-v1}{Hugging Face} 上开源了该模型，欢迎探索！

> We present AM-Thinking-v1, a 32B dense language model that advances the frontier of reasoning, embodying the collaborative spirit of open-source innovation. Outperforming DeepSeek-R1 and rivaling leading Mixture-of-Experts (MoE) models like Qwen3-235B-A22B and Seed1.5-Thinking, AM-Thinking-v1 achieves impressive scores of 85.3 on AIME 2024, 74.4 on AIME 2025, and 70.3 on LiveCodeBench, showcasing state-of-the-art mathematical and coding capabilities among open-source models of similar scale.
  Built entirely from the open-source Qwen2.5-32B base model and publicly available queries, AM-Thinking-v1 leverages a meticulously crafted post-training pipeline - combining supervised fine-tuning and reinforcement learning - to deliver exceptional reasoning capabilities. This work demonstrates that the open-source community can achieve high performance at the 32B scale, a practical sweet spot for deployment and fine-tuning. By striking a balance between top-tier performance and real-world usability, we hope AM-Thinking-v1 inspires further collaborative efforts to harness mid-scale models, pushing reasoning boundaries while keeping accessibility at the core of innovation. We have open-sourced our model on \href{https://huggingface.co/a-m-team/AM-Thinking-v1}{Hugging Face}.

[Arxiv](https://arxiv.org/abs/2505.08311)