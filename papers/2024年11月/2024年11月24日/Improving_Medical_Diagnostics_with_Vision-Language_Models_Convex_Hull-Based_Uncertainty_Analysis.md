# 借助视觉语言模型提升医疗诊断水平：基于凸包的不确定性分析

发布时间：2024年11月24日

`LLM应用` `医疗保健` `视觉语言模型`

> Improving Medical Diagnostics with Vision-Language Models: Convex Hull-Based Uncertainty Analysis

# 摘要

> 近年来，视觉语言模型（VLMs）在医疗保健、教育、金融和制造业等众多领域得到应用，成绩斐然。不过，VLMs的一致性和不确定性仍令人担忧，在医疗保健这类关键应用中尤甚，因为这些应用需要极高的信任度和可靠性。本文提出一种新方法，即在医疗保健应用中的视觉问答（VQA）里，运用凸包法评估VLMs响应的不确定性。选用LLM-CXR模型作为医疗VLM，在不同温度设定（即0.001、0.25、0.50、0.75和1.00）下为给定提示生成响应。结果表明，LLM-CXR VLM在较高温度设定下具有高度不确定性。实验结果凸显了VLMs响应中不确定性的重要性，在医疗保健应用中更是如此。

> In recent years, vision-language models (VLMs) have been applied to various fields, including healthcare, education, finance, and manufacturing, with remarkable performance. However, concerns remain regarding VLMs' consistency and uncertainty, particularly in critical applications such as healthcare, which demand a high level of trust and reliability. This paper proposes a novel approach to evaluate uncertainty in VLMs' responses using a convex hull approach on a healthcare application for Visual Question Answering (VQA). LLM-CXR model is selected as the medical VLM utilized to generate responses for a given prompt at different temperature settings, i.e., 0.001, 0.25, 0.50, 0.75, and 1.00. According to the results, the LLM-CXR VLM shows a high uncertainty at higher temperature settings. Experimental outcomes emphasize the importance of uncertainty in VLMs' responses, especially in healthcare applications.

[Arxiv](https://arxiv.org/abs/2412.00056)