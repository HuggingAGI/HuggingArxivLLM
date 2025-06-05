# 修正稀疏注意力机制

发布时间：2025年06月04日

`LLM应用` `人工智能`

> Rectified Sparse Attention

# 摘要

> 高效长序列生成是大型语言模型面临的关键挑战。近期的稀疏解码方法虽然提升了效率，但因KV缓存错位导致近似误差累积，影响生成质量。为此，我们提出修正稀疏注意力（ReSA），一种结合块稀疏注意力与周期性密集修正的创新方法。通过在固定间隔使用密集前向传递刷新KV缓存，ReSA有效限制误差累积，保持与预训练分布的一致性。在数学推理、语言建模和检索任务中，ReSA不仅显著提升了效率，还实现了近乎无损的生成质量。特别在256K序列长度的解码中，ReSA实现了高达2.42倍的端到端加速，成为可扩展长上下文推理的实际解决方案。代码可在https://aka.ms/ReSA-LM获取。

> Efficient long-sequence generation is a critical challenge for Large Language Models. While recent sparse decoding methods improve efficiency, they suffer from KV cache misalignment, where approximation errors accumulate and degrade generation quality. In this work, we propose Rectified Sparse Attention (ReSA), a simple yet effective method that combines block-sparse attention with periodic dense rectification. By refreshing the KV cache at fixed intervals using a dense forward pass, ReSA bounds error accumulation and preserves alignment with the pretraining distribution. Experiments across math reasoning, language modeling, and retrieval tasks demonstrate that ReSA achieves near-lossless generation quality with significantly improved efficiency. Notably, ReSA delivers up to 2.42$\times$ end-to-end speedup under decoding at 256K sequence length, making it a practical solution for scalable long-context inference. Code is available at https://aka.ms/ReSA-LM.

[Arxiv](https://arxiv.org/abs/2506.04108)