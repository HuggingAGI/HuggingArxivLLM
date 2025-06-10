# 比特级 BPE：突破字节边界限制

发布时间：2025年06月09日

`LLM应用

理由：这篇论文讨论了在大型语言模型中优化子词分词技术，特别是针对CJK语言和表情符号的处理，提出了一种压缩技术来提高训练和推理效率。这属于模型应用中的优化和实际问题解决，因此归类为LLM应用。` `文本处理`

> Bit-level BPE: Below the byte boundary

# 摘要

> 字节级回退在子词分词中已经成为常见做法，尤其在大型语言模型中。它尤其擅长防止OOV（未登录词），在大型模型中表现尤为突出。然而，将字符分解为字节会显著增加CJK语言（中文、日语、韩语）和表情符号等字符多样化场景的长尾标记序列长度，从而导致训练和推理时间延长。为了解决这一问题，我们提出了一种简单的无损压缩技术，可有效减少序列长度。

> Byte-level fallbacks for subword tokenization have become a common practice in large language models. In particular, it has been demonstrated to be incredibly effective as a pragmatic solution for preventing OOV, especially in the context of larger models. However, breaking a character down to individual bytes significantly increases the sequence length for long-tail tokens in languages such as Chinese, Japanese, and Korean (CJK) and other character-diverse contexts such as emoji. The increased sequence length results in longer computation during both training and inference. In this work, we propose a simple compression technique that reduces the sequence length losslessly.

[Arxiv](https://arxiv.org/abs/2506.07541)