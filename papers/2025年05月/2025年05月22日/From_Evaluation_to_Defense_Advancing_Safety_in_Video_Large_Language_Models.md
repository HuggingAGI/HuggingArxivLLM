# 从评估到防御，推动视频大语言模型的安全性提升

发布时间：2025年05月22日

`LLM应用` `视频安全` `多模态`

> From Evaluation to Defense: Advancing Safety in Video Large Language Models

# 摘要

> 尽管基于图像的大型语言模型的安全风险已得到广泛研究，但视频版（Video LLMs）的安全性却鲜有深入探讨。为系统研究这一问题，我们推出了VideoSafetyBench (VSB-77k)——首个大规模、文化多元的视频LLM安全基准测试，包含77,646个视频-查询对，覆盖10个语言社区的19个主要风险类别。我们发现，引入视频模态使安全性能平均下降42.3%，揭示了多模态攻击利用中的系统性风险。为应对这一漏洞，我们提出VideoSafety-R1，一个双阶段框架，通过两大创新实现前所未有的安全提升：（1）警报令牌引导的安全微调（AT-SFT）将可学习的警报令牌注入视觉和文本序列，通过多任务目标实现跨模态的显式危害感知。（2）随后，基于规则奖励的双模态验证的安全引导GRPO通过动态策略优化增强防御推理。这些组件协同作用，将安全对齐从被动危害识别转向主动推理。该框架在VSB-Eval-HH上实现了65.1%的性能提升，并在图像安全数据集MMBench、VLGuard和FigStep上分别提升了59.1%、44.3%和15.0%。我们的代码可在补充材料中获取。警告：本文包含有害语言和视频示例，建议读者自行斟酌阅读。


> While the safety risks of image-based large language models have been extensively studied, their video-based counterparts (Video LLMs) remain critically under-examined. To systematically study this problem, we introduce \textbf{VideoSafetyBench (VSB-77k) - the first large-scale, culturally diverse benchmark for Video LLM safety}, which compromises 77,646 video-query pairs and spans 19 principal risk categories across 10 language communities. \textit{We reveal that integrating video modality degrades safety performance by an average of 42.3\%, exposing systemic risks in multimodal attack exploitation.} To address this vulnerability, we propose \textbf{VideoSafety-R1}, a dual-stage framework achieving unprecedented safety gains through two innovations: (1) Alarm Token-Guided Safety Fine-Tuning (AT-SFT) injects learnable alarm tokens into visual and textual sequences, enabling explicit harm perception across modalities via multitask objectives. (2) Then, Safety-Guided GRPO enhances defensive reasoning through dynamic policy optimization with rule-based rewards derived from dual-modality verification. These components synergize to shift safety alignment from passive harm recognition to active reasoning. The resulting framework achieves a 65.1\% improvement on VSB-Eval-HH, and improves by 59.1\%, 44.3\%, and 15.0\% on the image safety datasets MMBench, VLGuard, and FigStep, respectively. \textit{Our codes are available in the supplementary materials.} \textcolor{red}{Warning: This paper contains examples of harmful language and videos, and reader discretion is recommended.}

[Arxiv](https://arxiv.org/abs/2505.16643)