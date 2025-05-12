# 基于拉格朗日插值的LLM文本水印技术

发布时间：2025年05月08日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）生成文本的归属问题，并提出了一种基于拉格朗日插值的水印技术来解决这一问题。虽然它涉及LLMs的安全性和归属问题，但其核心是应用层面的解决方案，而不是LLMs的理论或架构改进。因此，它属于LLM应用类别。` `网络安全` `数字内容安全`

> LLM-Text Watermarking based on Lagrange Interpolation

# 摘要

> 大型语言模型 (LLMs) 的快速发展使其成为许多人工智能和机器学习驱动的人机交互的基础技术。在这一背景下，我们面临一个关键挑战：如何确定LLM生成文本的归属，无论是归属到具体的语言模型，还是归属到生成文本的个人用户。这对于打击 misinformation、假新闻、误解和剽窃至关重要。解决这一问题的关键技术之一是水印技术。
    本研究提出了一种基于拉格朗日插值的 LLM 生成文本水印方案，即使文本被对手大量涂改，仍可恢复秘密作者身份。核心技术是嵌入一系列连续的点 (x, f(x))，这些点位于同一条直线上。x 坐标通过线性反馈移位寄存器 (LFSR) 生成伪随机数（当安全不是首要考虑时），或使用密码学安全的 NFSR（适用于高安全场景）。该方案的效率及其在对抗性修改下的鲁棒性得到了分析。实验结果表明，该方法非常有效，即使在仅三个点存活于对抗性操作的情况下，仍能恢复作者身份。

> The rapid advancement of LLMs (Large Language Models) has established them as a foundational technology for many AI and ML powered human computer interactions. A critical challenge in this context is the attribution of LLM-generated text, either to the specific language model used or to the individual user who generated it. This is essential for combating misinformation, fake news, misinterpretation, and plagiarism. One of the key techniques for addressing this issue is watermarking.
  This work presents a watermarking scheme for LLM-generated text based on Lagrange interpolation, which enables the recovery of a secret author identity even when the text has been heavily redacted by an adversary. The core idea is to embed a continuous sequence of points (x, f(x)) that lie on a single straight line. The x-coordinates are generated pseudorandomly using either an LFSR (when security is not a priority) or a cryptographically secure NFSR for high-security applications. The scheme efficiency and resilience to adversarial modifications are analysed. Experimental results show that the proposed method is highly effective, allowing the recovery of the author identity when as few as three points survive adversarial manipulation.

[Arxiv](https://arxiv.org/abs/2505.05712)