# 基于图像的机器人地理定位：黑箱视觉语言模型是否已达标？

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要探讨了视觉-语言模型（VLMs）在图像地理定位中的应用，特别是作为独立的零-shot地理定位系统的潜力。虽然VLMs与传统的LLMs有所不同，但它们都属于广义上的语言模型应用范畴。论文的研究重点在于如何利用这些模型进行地理定位，并评估其在不同场景下的表现，这属于LLM在实际应用中的探索。因此，将其分类为LLM应用是合适的。` `机器人` `地理定位`

> Image-based Geo-localization for Robotics: Are Black-box Vision-Language Models there yet?

# 摘要

> 视觉-语言模型（VLMs）的进展为图像地理定位的机器人应用带来了新的机遇，地理定位问题是指仅凭视觉数据确定地点的地理坐标。最近的研究聚焦于将VLM用作地理定位的嵌入提取器，但最先进的VLM往往只能通过API访问，且存在诸多限制：无法获取训练数据、模型特征和梯度；无法重新训练；预测次数可能受API限制；通常禁止在模型输出上进行训练；查询是开放式的。将VLM作为独立的零-shot地理定位系统，仅使用单一文本提示的研究尚属空白。为此，本文首次系统性地研究了在现实约束的黑箱环境中，一些顶尖VLM作为独立零-shot地理定位系统的潜力。我们深入探讨了三种场景：a) 固定文本提示；b) 语义等效的文本提示；c) 语义等效的查询图像。此外，我们还考虑了VLM的自回归和概率生成特性，在评估其地理定位能力时，除了传统准确性外，还引入了模型一致性作为衡量标准。本研究为不同VLM在上述场景中的表现提供了新的洞见。

> The advances in Vision-Language models (VLMs) offer exciting opportunities for robotic applications involving image geo-localization, the problem of identifying the geo-coordinates of a place based on visual data only. Recent research works have focused on using a VLM as embeddings extractor for geo-localization, however, the most sophisticated VLMs may only be available as black boxes that are accessible through an API, and come with a number of limitations: there is no access to training data, model features and gradients; retraining is not possible; the number of predictions may be limited by the API; training on model outputs is often prohibited; and queries are open-ended. The utilization of a VLM as a stand-alone, zero-shot geo-localization system using a single text-based prompt is largely unexplored. To bridge this gap, this paper undertakes the first systematic study, to the best of our knowledge, to investigate the potential of some of the state-of-the-art VLMs as stand-alone, zero-shot geo-localization systems in a black-box setting with realistic constraints. We consider three main scenarios for this thorough investigation: a) fixed text-based prompt; b) semantically-equivalent text-based prompts; and c) semantically-equivalent query images. We also take into account the auto-regressive and probabilistic generation process of the VLMs when investigating their utility for geo-localization task by using model consistency as a metric in addition to traditional accuracy. Our work provides new insights in the capabilities of different VLMs for the above-mentioned scenarios.

[Arxiv](https://arxiv.org/abs/2501.16947)