# MoSEs：基于条件阈值的文体专家混合模型的不确定性感知AI生成文本检测

发布时间：2025年09月02日

`LLM应用` `基础理论`

> MoSEs: Uncertainty-Aware AI-Generated Text Detection via Mixture of Stylistics Experts with Conditional Thresholds

# 摘要

> 大型语言模型的飞速发展引发了公众对其潜在滥用风险的高度关注，构建可信的AI生成文本检测系统因此变得至关重要。现有方法往往忽略风格建模，且多依赖静态阈值，这严重制约了检测效果。为此，本文提出风格专家混合体（MoSEs）框架，通过条件阈值估计实现风格感知的不确定性量化。该框架核心包含三大组件：风格参考库（SRR）、风格感知路由器（SAR）和条件阈值估计器（CTE）。面对输入文本时，SRR会激活库中匹配的参考数据并传递给CTE；CTE随后联合建模语言统计特性与语义特征，动态确定最优阈值。结合判别分数，MoSEs可输出带有对应置信度的预测标签。实验表明，该框架较基线检测性能平均提升11.34%，在低资源场景下更实现了39.15%的显著提升。相关代码已开源至https://github.com/creator-xi/MoSEs。

> The rapid advancement of large language models has intensified public concerns about the potential misuse. Therefore, it is important to build trustworthy AI-generated text detection systems. Existing methods neglect stylistic modeling and mostly rely on static thresholds, which greatly limits the detection performance. In this paper, we propose the Mixture of Stylistic Experts (MoSEs) framework that enables stylistics-aware uncertainty quantification through conditional threshold estimation. MoSEs contain three core components, namely, the Stylistics Reference Repository (SRR), the Stylistics-Aware Router (SAR), and the Conditional Threshold Estimator (CTE). For input text, SRR can activate the appropriate reference data in SRR and provide them to CTE. Subsequently, CTE jointly models the linguistic statistical properties and semantic features to dynamically determine the optimal threshold. With a discrimination score, MoSEs yields prediction labels with the corresponding confidence level. Our framework achieves an average improvement 11.34% in detection performance compared to baselines. More inspiringly, MoSEs shows a more evident improvement 39.15% in the low-resource case. Our code is available at https://github.com/creator-xi/MoSEs.

[Arxiv](https://arxiv.org/abs/2509.02499)