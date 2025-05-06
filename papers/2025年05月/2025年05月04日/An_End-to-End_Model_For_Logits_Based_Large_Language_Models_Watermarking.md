# 基于Logits的大型语言模型水印端到端模型

发布时间：2025年05月04日

`LLM应用` `知识产权` `内容安全`

> An End-to-End Model For Logits Based Large Language Models Watermarking

# 摘要

> 大型语言模型（LLMs）的兴起引发了对AIGC版权保护和来源追踪的广泛关注，推动了对先进检测技术的需求。被动检测方法误报率较高，而基于logits或采样操作的主动水印技术则提供了更有效的保护方案。现有的LLM水印方法虽然在原始内容上表现良好，但在文本被修改时性能大幅下降，甚至可能引入影响LLM下游任务表现的偏差。这些方法未能在文本质量和鲁棒性之间取得理想平衡，主要因为缺乏对编码器和解码器的端到端优化。本文提出了一种用于水印LLM生成文本的新型端到端logits扰动方法。通过联合优化，我们的方法在保持高质量的同时显著提升了鲁棒性。针对端到端训练中的非可微操作问题，我们创新性地引入了在线提示技术，利用实时LLM作为可微替代方案。实验结果表明，我们的方法在鲁棒性方面表现优异，在改写测试中比无失真方法高出37-39%，平均高出17.2%，同时在文本困惑度和下游任务方面与这些无失真方法保持相当的文本质量。此外，我们的方法具有良好的通用性，可轻松应用于不同类型的LLMs。

> The rise of LLMs has increased concerns over source tracing and copyright protection for AIGC, highlighting the need for advanced detection technologies. Passive detection methods usually face high false positives, while active watermarking techniques using logits or sampling manipulation offer more effective protection. Existing LLM watermarking methods, though effective on unaltered content, suffer significant performance drops when the text is modified and could introduce biases that degrade LLM performance in downstream tasks. These methods fail to achieve an optimal tradeoff between text quality and robustness, particularly due to the lack of end-to-end optimization of the encoder and decoder. In this paper, we introduce a novel end-to-end logits perturbation method for watermarking LLM-generated text. By jointly optimization, our approach achieves a better balance between quality and robustness. To address non-differentiable operations in the end-to-end training pipeline, we introduce an online prompting technique that leverages the on-the-fly LLM as a differentiable surrogate. Our method achieves superior robustness, outperforming distortion-free methods by 37-39% under paraphrasing and 17.2% on average, while maintaining text quality on par with these distortion-free methods in terms of text perplexity and downstream tasks. Our method can be easily generalized to different LLMs.

[Arxiv](https://arxiv.org/abs/2505.02344)