# SUMMA：用于广告摘要的多模态大型语言模型

发布时间：2025年08月28日

`LLM应用` `媒体与娱乐`

> SUMMA: A Multimodal Large Language Model for Advertisement Summarization

# 摘要

> 深入理解多模态视频广告对于优化短视频平台的查询-广告匹配与相关性排序、提升广告效果及用户体验至关重要。然而，具有高商业价值的多模态信息长期以来难以有效利用，这主要源于对高度压缩视频嵌入的过度依赖。为此，我们提出SUMMA（Summarizing MultiModal Ads的缩写）——一种多模态模型，它能自动将视频广告处理为突出核心商业价值的摘要，从而提升其在抖音搜索广告系统中的可理解性与排序表现。SUMMA采用两阶段训练策略：先基于包含视频帧及语音识别/光学字符识别文本的领域数据进行多模态监督微调，再结合混合奖励机制开展强化学习，最终生成兼具商业价值与可解释性的摘要。我们将SUMMA生成的摘要集成到生产流程中，直接优化了实际搜索广告系统的候选检索与相关性排序环节。离线与在线实验均显示出相较于基线模型的显著提升，其中在线结果表明广告收入实现了统计显著的1.5%增长。本研究开创了多模态信息浓缩为代表性文本的新范式，在检索与推荐场景中有效实现了视觉广告内容与用户查询意图的精准对齐。

> Understanding multimodal video ads is crucial for improving query-ad matching and relevance ranking on short video platforms, enhancing advertising effectiveness and user experience. However, the effective utilization of multimodal information with high commercial value still largely constrained by reliance on highly compressed video embeddings-has long been inadequate. To address this, we propose SUMMA (the abbreviation of Summarizing MultiModal Ads), a multimodal model that automatically processes video ads into summaries highlighting the content of highest commercial value, thus improving their comprehension and ranking in Douyin search-advertising systems. SUMMA is developed via a two-stage training strategy-multimodal supervised fine-tuning followed by reinforcement learning with a mixed reward mechanism-on domain-specific data containing video frames and ASR/OCR transcripts, generating commercially valuable and explainable summaries. We integrate SUMMA-generated summaries into our production pipeline, directly enhancing the candidate retrieval and relevance ranking stages in real search-advertising systems. Both offline and online experiments show substantial improvements over baselines, with online results indicating a statistically significant 1.5% increase in advertising revenue. Our work establishes a novel paradigm for condensing multimodal information into representative texts, effectively aligning visual ad content with user query intent in retrieval and recommendation scenarios.

[Arxiv](https://arxiv.org/abs/2508.20582)