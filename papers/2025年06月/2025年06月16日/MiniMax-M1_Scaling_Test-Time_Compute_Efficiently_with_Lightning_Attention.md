# MiniMax-M1: 借助闪电注意力机制实现测试时间计算资源的高效扩展

发布时间：2025年06月16日

`LLM应用` `软件工程` `人工智能`

> MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention

# 摘要

> 我们很高兴推出 MiniMax-M1，这是全球首个开放权重、大规模混合注意力推理模型。它结合了混合专家（MoE）架构和闪电注意力机制，基于我们之前开发的 MiniMax-Text-01 模型，该模型拥有 4560 亿总参数量，每 token 激活参数量为 459 亿。MiniMax-M1 原生支持 100 万个 token 的上下文长度，是 DeepSeek R1 上下文大小的 8 倍。其独特的闪电注意力机制还实现了测试阶段计算的高效扩展。这些特性使 MiniMax-M1 在处理长输入和深度思考的复杂任务中表现尤为出色。在训练方面，我们采用了大规模强化学习（RL），涵盖基于沙盒和真实世界软件工程环境的多样化场景。除了 M1 本身在 RL 训练中的效率优势，我们还创新性地提出了 CISPO 算法，进一步提升了 RL 的效率。CISPO 通过裁剪重要性采样权重而非更新 token，在性能上优于其他竞争性的 RL 变体。结合混合注意力和 CISPO，MiniMax-M1 在 512 块 H800 GPU 上完成完整的 RL 训练仅需三周时间，租用成本仅为 534,700 美元。我们发布了两个版本的 MiniMax-M1 模型，分别具有 40K 和 80K 的思考预算，其中 40K 模型代表了 80K 训练的中间阶段。在标准基准测试中，我们的模型表现优异，与强大的开放权重模型（如原始的 DeepSeek-R1 和 Qwen3-235B）相比具有可比性或更优性能，尤其在复杂软件工程、工具利用和长上下文任务方面表现突出。现在，MiniMax-M1 已在 https://github.com/MiniMax-AI/MiniMax-M1 上公开发布，欢迎体验。

> We introduce MiniMax-M1, the world's first open-weight, large-scale hybrid-attention reasoning model. MiniMax-M1 is powered by a hybrid Mixture-of-Experts (MoE) architecture combined with a lightning attention mechanism. The model is developed based on our previous MiniMax-Text-01 model, which contains a total of 456 billion parameters with 45.9 billion parameters activated per token. The M1 model natively supports a context length of 1 million tokens, 8x the context size of DeepSeek R1. Furthermore, the lightning attention mechanism in MiniMax-M1 enables efficient scaling of test-time compute. These properties make M1 particularly suitable for complex tasks that require processing long inputs and thinking extensively. MiniMax-M1 is trained using large-scale reinforcement learning (RL) on diverse problems including sandbox-based, real-world software engineering environments. In addition to M1's inherent efficiency advantage for RL training, we propose CISPO, a novel RL algorithm to further enhance RL efficiency. CISPO clips importance sampling weights rather than token updates, outperforming other competitive RL variants. Combining hybrid-attention and CISPO enables MiniMax-M1's full RL training on 512 H800 GPUs to complete in only three weeks, with a rental cost of just $534,700. We release two versions of MiniMax-M1 models with 40K and 80K thinking budgets respectively, where the 40K model represents an intermediate phase of the 80K training. Experiments on standard benchmarks show that our models are comparable or superior to strong open-weight models such as the original DeepSeek-R1 and Qwen3-235B, with particular strengths in complex software engineering, tool utilization, and long-context tasks. We publicly release MiniMax-M1 at https://github.com/MiniMax-AI/MiniMax-M1.

[Arxiv](https://arxiv.org/abs/2506.13585)