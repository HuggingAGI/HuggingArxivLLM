# # 合成视频有用吗？合成视频检索评估基准

发布时间：2025年07月03日

`其他` `视频生成` `视频检索`

> Are Synthetic Videos Useful? A Benchmark for Retrieval-Centric Evaluation of Synthetic Videos

# 摘要

> 文本到视频（T2V）合成技术发展迅猛，但现有评估指标主要关注视觉质量和时间一致性，对合成视频在下游任务如文本到视频检索（TVR）中的实际表现缺乏深入理解。为此，我们推出SynTVA——一个全新的数据集和基准，专注于评估合成视频在构建检索模型中的实用性。基于从MSRVTT训练集分割中提取的800个多样化用户查询，我们利用最先进的T2V模型生成合成视频，并从四个关键语义对齐维度对每对视频-文本进行标注：对象与场景、动作、属性和提示保真度。我们的评估框架将通用视频质量评估（VQA）指标与这些对齐分数相关联，深入分析其对下游TVR性能的预测能力。为探索扩展路径，我们进一步开发了一个自动评估器，能够从现有指标中智能估计对齐质量。SynTVA的价值不仅限于基准测试，我们的研究还表明，它在数据集增强方面具有重要价值，能够精准筛选出高实用性的合成样本，显著提升TVR效果。项目页面和数据集详情请访问https://jasoncodemaker.github.io/SynTVA/。

> Text-to-video (T2V) synthesis has advanced rapidly, yet current evaluation metrics primarily capture visual quality and temporal consistency, offering limited insight into how synthetic videos perform in downstream tasks such as text-to-video retrieval (TVR). In this work, we introduce SynTVA, a new dataset and benchmark designed to evaluate the utility of synthetic videos for building retrieval models. Based on 800 diverse user queries derived from MSRVTT training split, we generate synthetic videos using state-of-the-art T2V models and annotate each video-text pair along four key semantic alignment dimensions: Object \& Scene, Action, Attribute, and Prompt Fidelity. Our evaluation framework correlates general video quality assessment (VQA) metrics with these alignment scores, and examines their predictive power for downstream TVR performance. To explore pathways of scaling up, we further develop an Auto-Evaluator to estimate alignment quality from existing metrics. Beyond benchmarking, our results show that SynTVA is a valuable asset for dataset augmentation, enabling the selection of high-utility synthetic samples that measurably improve TVR outcomes. Project page and dataset can be found at https://jasoncodemaker.github.io/SynTVA/.

[Arxiv](https://arxiv.org/abs/2507.02316)