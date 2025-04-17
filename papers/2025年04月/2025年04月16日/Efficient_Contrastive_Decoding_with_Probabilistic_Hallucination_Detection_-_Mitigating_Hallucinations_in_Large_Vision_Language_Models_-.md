# 高效对比解码结合概率幻觉检测——解决大型视觉语言模型中的幻觉问题

发布时间：2025年04月16日

`LLM应用` `人工智能` `计算机视觉`

> Efficient Contrastive Decoding with Probabilistic Hallucination Detection - Mitigating Hallucinations in Large Vision Language Models -

# 摘要

> 尽管大型视觉语言模型（LVLMs）近期取得了进展，但这些模型依然面临生成不符合输入图像的幻觉回应的问题。为了解决这一难题，我们提出了高效对比解码（ECD）。这是一种简单却有效的方法，它通过概率幻觉检测机制，在推理过程中将输出分布引导至更符合上下文的准确答案。ECD通过对比令牌概率和幻觉分数，巧妙地从原始分布中剔除幻觉概念，从而有效抑制幻觉现象。值得注意的是，我们的方法具有广泛的适用性，可以应用于任何开源LVLM，且无需额外的模型训练。我们在多个基准数据集和不同的LVLM上进行了全面评估，实验结果表明，ECD在缓解幻觉问题方面表现出色，不仅在LVLM基准性能上优于现有方法，而且在计算效率方面也实现了显著提升。

> Despite recent advances in Large Vision Language Models (LVLMs), these models still suffer from generating hallucinatory responses that do not align with the visual input provided. To mitigate such hallucinations, we introduce Efficient Contrastive Decoding (ECD), a simple method that leverages probabilistic hallucination detection to shift the output distribution towards contextually accurate answers at inference time. By contrasting token probabilities and hallucination scores, ECD subtracts hallucinated concepts from the original distribution, effectively suppressing hallucinations. Notably, our proposed method can be applied to any open-source LVLM and does not require additional LVLM training. We evaluate our method on several benchmark datasets and across different LVLMs. Our experiments show that ECD effectively mitigates hallucinations, outperforming state-of-the-art methods with respect to performance on LVLM benchmarks and computation time.

[Arxiv](https://arxiv.org/abs/2504.12137)