# 释放LLMs的真正潜力：反馈触发的自校正与长期多路径解码

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Unleashing the True Potential of LLMs: A Feedback-Triggered Self-Correction with Long-Term Multipath Decoding

# 摘要

> 大型语言模型（LLMs）在各类任务中表现卓越，但在推理时容易生成错误内容，这仍是亟待解决的关键难题。尽管自校正方法为解决这一问题提供了可能，但其效果受限于两个固有缺陷：（1）缺乏用于错误定位的可靠指导信号；（2）传统下一个token解码范式限制了推理深度。为解决这些问题，我们提出了反馈触发再生（FTR）——一种将用户反馈与增强解码动态相结合的新型框架。具体来说，FTR仅在收到用户负面反馈时才激活响应再生，这样既能避免错误自我评估引发的错误传播，又能保留原本正确的输出。此外，我们引入了长期多路径（LTM）解码，该方法通过延迟序列评估对多条推理路径进行系统性探索，有效克服了标准下一个token预测的短视决策问题。在数学推理和代码生成基准上的大量实验表明，我们的框架相较于最先进的基于提示的自校正方法，实现了持续且显著的性能提升。

> Large Language Models (LLMs) have achieved remarkable performance across diverse tasks, yet their susceptibility to generating incorrect content during inference remains a critical unsolved challenge. While self-correction methods offer potential solutions, their effectiveness is hindered by two inherent limitations: (1) the absence of reliable guidance signals for error localization, and (2) the restricted reasoning depth imposed by conventional next-token decoding paradigms. To address these issues, we propose Feedback-Triggered Regeneration (FTR), a novel framework that synergizes user feedback with enhanced decoding dynamics. Specifically, FTR activates response regeneration only upon receiving negative user feedback, thereby circumventing error propagation from faulty self-assessment while preserving originally correct outputs. Furthermore, we introduce Long-Term Multipath (LTM) decoding, which enables systematic exploration of multiple reasoning trajectories through delayed sequence evaluation, effectively overcoming the myopic decision-making characteristic of standard next-token prediction. Extensive experiments on mathematical reasoning and code generation benchmarks demonstrate that our framework achieves consistent and significant improvements over state-of-the-art prompt-based self-correction methods.

[Arxiv](https://arxiv.org/abs/2509.07676)