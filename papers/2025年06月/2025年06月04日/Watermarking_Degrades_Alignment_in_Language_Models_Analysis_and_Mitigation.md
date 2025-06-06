# 水印技术会削弱语言模型的对齐效果：分析及应对策略

发布时间：2025年06月04日

`LLM理论` `人工智能`

> Watermarking Degrades Alignment in Language Models: Analysis and Mitigation

# 摘要

> 大型语言模型（LLMs）的水印技术对输出质量产生显著影响，但其对真实度、安全性和有用性的影响却鲜有深入研究。本文系统分析了两种流行的水印方法——Gumbel和KGW——对四个对齐LLMs的核心对齐特性的影响。实验结果揭示了两种截然不同的退化模式：守护减弱，即增强有用性削弱了模型安全性；以及守护增强，即过度谨慎降低了模型有用性。这些模式源于水印引发的令牌分布变化，揭示了对齐目标之间存在的根本性矛盾。
为了缓解这些退化现象，我们提出了对齐重采样（AR），这是一种推理时的采样方法，利用外部奖励模型恢复对齐。我们推导了预期奖励评分随样本量增加的理论下限，并实证表明仅需2-4次带水印的生成即可有效恢复或超越基线（无水印）对齐评分。为克服标准Gumbel水印响应多样性有限的限制，我们的改进实现放弃了严格的无失真性，同时保持了强大的可检测性，确保与AR兼容。实验结果证实，AR在两种水印方法中均成功恢复了基线对齐，同时保持了水印的高检测性。本研究揭示了水印强度与模型对齐之间的关键平衡，为负责任地部署带水印的LLMs提供了实用的推理时解决方案。

> Watermarking techniques for large language models (LLMs) can significantly impact output quality, yet their effects on truthfulness, safety, and helpfulness remain critically underexamined. This paper presents a systematic analysis of how two popular watermarking approaches-Gumbel and KGW-affect these core alignment properties across four aligned LLMs. Our experiments reveal two distinct degradation patterns: guard attenuation, where enhanced helpfulness undermines model safety, and guard amplification, where excessive caution reduces model helpfulness. These patterns emerge from watermark-induced shifts in token distribution, surfacing the fundamental tension that exists between alignment objectives.
  To mitigate these degradations, we propose Alignment Resampling (AR), an inference-time sampling method that uses an external reward model to restore alignment. We establish a theoretical lower bound on the improvement in expected reward score as the sample size is increased and empirically demonstrate that sampling just 2-4 watermarked generations effectively recovers or surpasses baseline (unwatermarked) alignment scores. To overcome the limited response diversity of standard Gumbel watermarking, our modified implementation sacrifices strict distortion-freeness while maintaining robust detectability, ensuring compatibility with AR. Experimental results confirm that AR successfully recovers baseline alignment in both watermarking approaches, while maintaining strong watermark detectability. This work reveals the critical balance between watermark strength and model alignment, providing a simple inference-time solution to responsibly deploy watermarked LLMs in practice.

[Arxiv](https://arxiv.org/abs/2506.04462)