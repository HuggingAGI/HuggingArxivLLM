# 在思考不足与过度思考之间：关于大型语言模型中推理长度与正确性的实证研究

发布时间：2025年04月30日

`LLM理论` `人工智能`

> Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs

# 摘要

> 大型语言模型（LLMs）正在日益优化以支持长推理过程，但更长的推理并不总是带来更优性能。本文系统性地研究了推理长度与答案准确性之间的关系，发现LLMs往往存在“思考失衡”现象：简单问题过度思考，输出冗长；难题思考不足，在最需要的时候无法延长推理。这表明模型可能误判问题难度，未能恰当地调整回答长度。此外，我们还探讨了长度缩减的影响，采用了一种偏好优化算法，即使在不考虑答案准确性的情况下偏好更短的回答。实验结果表明，在保持可接受准确性的前提下，生成长度可以大幅缩减。我们的发现凸显了生成长度作为推理行为的重要信号，并为进一步探索LLMs在推理长度适应方面的自我意识提供了动力。

> Large language models (LLMs) are increasingly optimized for long reasoning, under the assumption that more reasoning leads to better performance. However, emerging evidence suggests that longer responses can sometimes degrade accuracy rather than improve it. In this paper, we conduct a systematic empirical study of the relationship between reasoning length and answer correctness. We find that LLMs tend to overthink simple problems, generating unnecessarily long outputs, and underthink harder ones, failing to extend their reasoning when it is most needed. This indicates that models might misjudge problem difficulty and fail to calibrate their response length appropriately. Furthermore, we investigate the effects of length reduction with a preference optimization algorithm when simply preferring the shorter responses regardless of answer correctness. Experiments show that the generation length can be significantly reduced while maintaining acceptable accuracy. Our findings highlight generation length as a meaningful signal for reasoning behavior and motivate further exploration into LLMs' self-awareness in reasoning length adaptation.

[Arxiv](https://arxiv.org/abs/2505.00127)