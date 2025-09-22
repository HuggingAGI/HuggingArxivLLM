# REFER：基于频率框架提示缓解观点摘要中的偏见

发布时间：2025年09月19日

`LLM应用` `基础理论`

> REFER: Mitigating Bias in Opinion Summarisation via Frequency Framed Prompting

# 摘要

> 人们的观点千差万别，一份公正的摘要需全面反映这些不同视角。以往研究在利用大型语言模型（LLMs）生成观点摘要时，为实现公平性多依赖超参数调优或在提示词中提供真实分布信息。但这些方法存在实际局限：终端用户极少调整默认模型参数，而准确的分布信息往往也无法获取。认知科学研究显示，基于频率的表征能通过明确参考类别、减轻认知负荷，减少人类统计推理中的系统性偏差。本研究以此为基础，探讨基于频率框架的提示（REFER）是否能类似地提升LLM观点摘要的公平性。通过不同提示框架的系统性实验，我们借鉴了已知能改善人类推理的技术，以在语言模型中实现比抽象概率表征更高效的信息处理。结果显示，REFER能有效提升语言模型生成观点摘要时的公平性，且这种效应在更大规模的语言模型中，以及使用更强推理指令时尤为突出。

> Individuals express diverse opinions, a fair summary should represent these viewpoints comprehensively. Previous research on fairness in opinion summarisation using large language models (LLMs) relied on hyperparameter tuning or providing ground truth distributional information in prompts. However, these methods face practical limitations: end-users rarely modify default model parameters, and accurate distributional information is often unavailable. Building upon cognitive science research demonstrating that frequency-based representations reduce systematic biases in human statistical reasoning by making reference classes explicit and reducing cognitive load, this study investigates whether frequency framed prompting (REFER) can similarly enhance fairness in LLM opinion summarisation. Through systematic experimentation with different prompting frameworks, we adapted techniques known to improve human reasoning to elicit more effective information processing in language models compared to abstract probabilistic representations.Our results demonstrate that REFER enhances fairness in language models when summarising opinions. This effect is particularly pronounced in larger language models and using stronger reasoning instructions.

[Arxiv](https://arxiv.org/abs/2509.15723)