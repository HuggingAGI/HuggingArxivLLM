# 探究与增强大型多模态模型的时间一致性鲁棒性

发布时间：2025年05月20日

`LLM应用` `视频分析` `多模态模型`

> Investigating and Enhancing the Robustness of Large Multimodal Models Against Temporal Inconsistency

# 摘要

> 大型多模态模型（LMMs）在通用视频理解任务中表现优异，但在时间分析的鲁棒性方面仍有待深入研究。针对这一问题，我们提出了时间鲁棒性基准测试（TemRobBench），通过在视觉和文本模态中引入时间不一致性扰动，全面评估模型的鲁棒性。经过对16个主流LMM的测试，我们发现这些模型在对抗环境中过度依赖先验知识和文本上下文，而忽略了视频中实际的时间动态。为解决这一问题，我们设计了全景直接偏好优化（PanoDPO），引导模型同时融合视觉和语言特征偏好。实验结果表明，PanoDPO显著提升了模型在时间分析中的鲁棒性和可靠性。

> Large Multimodal Models (LMMs) have recently demonstrated impressive performance on general video comprehension benchmarks. Nevertheless, for broader applications, the robustness of their temporal analysis capability needs to be thoroughly investigated yet predominantly ignored. Motivated by this, we propose a novel temporal robustness benchmark (TemRobBench), which introduces temporal inconsistency perturbations separately at the visual and textual modalities to assess the robustness of models. We evaluate 16 mainstream LMMs and find that they exhibit over-reliance on prior knowledge and textual context in adversarial environments, while ignoring the actual temporal dynamics in the video. To mitigate this issue, we design panoramic direct preference optimization (PanoDPO), which encourages LMMs to incorporate both visual and linguistic feature preferences simultaneously. Experimental results show that PanoDPO can effectively enhance the model's robustness and reliability in temporal analysis.

[Arxiv](https://arxiv.org/abs/2505.14405)