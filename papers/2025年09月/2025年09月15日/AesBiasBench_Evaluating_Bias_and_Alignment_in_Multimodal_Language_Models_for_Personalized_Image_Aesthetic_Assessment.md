# AesBiasBench：评估多模态语言模型在个性化图像美学评估中的偏见与对齐

发布时间：2025年09月15日

`LLM应用` `媒体与娱乐`

> AesBiasBench: Evaluating Bias and Alignment in Multimodal Language Models for Personalized Image Aesthetic Assessment

# 摘要

> 多模态大型语言模型（MLLMs）正逐渐成为个性化图像美学评估（PIAA）的新选择，凭借可扩展性替代传统专家评估。但这类模型的预测结果可能暗藏偏差，而性别、年龄、教育程度等人口统计学特征正是背后推手。为此，我们提出AesBiasBench基准测试集，从两个互补维度评估MLLMs：（1）刻板印象偏差——通过衡量不同人口群体美学评估的差异来量化；（2）模型输出与真实人类美学偏好的一致性。该基准测试集包含三个子任务（美学感知、美学评估、共情），并提出结构化指标（IFD、NRD、AAS），可同时评估偏差与一致性。我们对19个MLLMs展开评估，涵盖GPT-4o、Claude-3.5-Sonnet等专有模型及InternVL-2.5、Qwen2.5-VL等开源模型。结果显示，模型规模越小，刻板印象偏差越明显；而规模较大的模型则与人类偏好更贴合。值得注意的是，纳入身份信息反而会加剧偏差，在情感判断任务中尤为突出。这些发现提示我们，在主观性视觉-语言任务中，建立考虑身份因素的评估框架至关重要。

> Multimodal Large Language Models (MLLMs) are increasingly applied in Personalized Image Aesthetic Assessment (PIAA) as a scalable alternative to expert evaluations. However, their predictions may reflect subtle biases influenced by demographic factors such as gender, age, and education. In this work, we propose AesBiasBench, a benchmark designed to evaluate MLLMs along two complementary dimensions: (1) stereotype bias, quantified by measuring variations in aesthetic evaluations across demographic groups; and (2) alignment between model outputs and genuine human aesthetic preferences. Our benchmark covers three subtasks (Aesthetic Perception, Assessment, Empathy) and introduces structured metrics (IFD, NRD, AAS) to assess both bias and alignment. We evaluate 19 MLLMs, including proprietary models (e.g., GPT-4o, Claude-3.5-Sonnet) and open-source models (e.g., InternVL-2.5, Qwen2.5-VL). Results indicate that smaller models exhibit stronger stereotype biases, whereas larger models align more closely with human preferences. Incorporating identity information often exacerbates bias, particularly in emotional judgments. These findings underscore the importance of identity-aware evaluation frameworks in subjective vision-language tasks.

[Arxiv](https://arxiv.org/abs/2509.11620)