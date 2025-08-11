# Leveraging LLMs for Scalable Non-intrusive Speech Quality Assessment
借助大型语言模型实现可扩展的非侵入式语音质量评估

发布时间：2025年08月08日

`LLM应用` `语音质量评估`

> Leveraging LLMs for Scalable Non-intrusive Speech Quality Assessment

# 摘要

> 非侵入式语音质量评估（SQA）系统在实际应用中面临训练数据有限和人工标注成本高昂的挑战，限制了其在实时会议通话中的应用。为解决这一问题，我们提出利用大型语言模型（LLMs）作为伪评分器，构建了包含101,129个语音片段的LibriAugmented数据集，这些片段由微调后的听觉LLM（Vicuna-7b-v1.5）标注了模拟降质信息。我们对比了三种训练策略：人工标注数据、LLM标注数据，以及两阶段方法（先基于LLM标签预训练，再基于人工标签微调），并使用DNSMOS Pro和DeePMOS两种评估方法进行测试。实验结果表明，尽管LLM标注的训练效果与人工标注相比仍有差距，但两阶段方法显著提升了模型的泛化性能（例如，在NISQA_TEST_LIVETALK数据集上，DNSMOS Pro的PCC值从0.55提升至0.63，在带混响的腾讯数据集上，PCC值从0.65提升至0.73）。我们的研究展示了将LLMs作为伪评分器在语音质量评估中的潜力，为解决数据限制问题提供了一种经济有效的解决方案。

> Non-intrusive speech quality assessment (SQA) systems suffer from limited training data and costly human annotations, hindering their generalization to real-time conferencing calls. In this work, we propose leveraging large language models (LLMs) as pseudo-raters for speech quality to address these data bottlenecks. We construct LibriAugmented, a dataset consisting of 101,129 speech clips with simulated degradations labeled by a fine-tuned auditory LLM (Vicuna-7b-v1.5). We compare three training strategies: using human-labeled data, using LLM-labeled data, and a two-stage approach (pretraining on LLM labels, then fine-tuning on human labels), using both DNSMOS Pro and DeePMOS. We test on several datasets across languages and quality degradations. While LLM-labeled training yields mixed results compared to human-labeled training, we provide empirical evidence that the two-stage approach improves the generalization performance (e.g., DNSMOS Pro achieves 0.63 vs. 0.55 PCC on NISQA_TEST_LIVETALK and 0.73 vs. 0.65 PCC on Tencent with reverb). Our findings demonstrate the potential of using LLMs as scalable pseudo-raters for speech quality assessment, offering a cost-effective solution to the data limitation problem.

[Arxiv](https://arxiv.org/abs/2508.06284)