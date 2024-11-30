# 本研究致力于评估最新大型视觉-语言模型的实际效果，探究其在各类跨模态任务中的表现与价值。

发布时间：2024年03月07日

`Agent`

> Effectiveness Assessment of Recent Large Vision-Language Models

# 摘要

> 随着LVLM的到来，人工智能向着更广泛智能迈出了重大一步。但其在各类专业及一般任务上的实际效果尚需深入探究。本篇文章致力于全方位评价当前主流LVLM在专业与一般任务中的表现力，力求展现这些前沿技术的全貌。为了精准测评LVLM处理专业任务的能力，我们构建了一个囊括自然环境、医疗健康和工业生产三大领域的综合测试集，共包含六项极具挑战的任务，如显著物体、伪装及透明物体检测，以及息肉、皮肤病变检测和工业异常检测等。在视觉识别与定位方面，我们选取了最新开放源代码的MiniGPT-v2、LLaVA-1.5和Shikra这三款LVLM进行性能检验。同时，结合GPT-4V，我们还通过一系列实证实验来度量这些模型在对象计数、无厘头问答、功能推理、属性识别及空间关系推理等一般任务中的多模态理解能力。研究结果显示，这些模型在面对专业和一般任务时均表现出一定的局限性，这可能是受限于认知深度、对象臆想、文本-图像相互干扰以及复杂问题下的稳健性下降等因素。此项研究期望为LVLM的未来发展提供宝贵启示，助力其更好地适应通用及专业应用场景的需求。

> The advent of large vision-language models (LVLMs) represents a noteworthy advancement towards the pursuit of artificial general intelligence. However, the extent of their efficacy across both specialized and general tasks warrants further investigation. This article endeavors to evaluate the competency of popular LVLMs in specialized and general tasks, respectively, aiming to offer a comprehensive comprehension of these innovative methodologies. To gauge their efficacy in specialized tasks, we tailor a comprehensive testbed comprising three distinct scenarios: natural, healthcare, and industrial, encompassing six challenging tasks. These tasks include salient, camouflaged, and transparent object detection, as well as polyp and skin lesion detection, alongside industrial anomaly detection. We examine the performance of three recent open-source LVLMs -- MiniGPT-v2, LLaVA-1.5, and Shikra -- in the realm of visual recognition and localization. Moreover, we conduct empirical investigations utilizing the aforementioned models alongside GPT-4V, assessing their multi-modal understanding capacities in general tasks such as object counting, absurd question answering, affordance reasoning, attribute recognition, and spatial relation reasoning. Our investigations reveal that these models demonstrate limited proficiency not only in specialized tasks but also in general tasks. We delve deeper into this inadequacy and suggest several potential factors, including limited cognition in specialized tasks, object hallucination, text-to-image interference, and decreased robustness in complex problems. We hope this study would provide valuable insights for the future development of LVLMs, augmenting their power in coping with both general and specialized applications.

[Arxiv](https://arxiv.org/abs/2403.04306)