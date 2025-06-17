# 探究多模态大语言模型在视频理解中的可信度评估

发布时间：2025年06月14日

`LLM应用` `视频理解` `可信度评估`

> Understanding and Benchmarking the Trustworthiness in Multimodal LLMs for Video Understanding

# 摘要

> 近期，视频理解领域的多模态大语言模型（videoLLMs）取得了显著进展，增强了处理动态多模态数据的能力。然而，事实不准确、有害内容、偏见、幻觉和隐私风险等可信度问题，由于视频数据的时空复杂性，削弱了模型的可靠性。本研究引入了Trust-videoLLMs，一个全面评估视频LLMs的基准测试，涵盖真实性、安全性、鲁棒性、公平性和隐私性五个维度。该框架包含30个任务，使用改编、合成和标注的视频，评估动态视觉场景、跨模态互动以及现实世界的安全问题。我们对23个最先进的视频LLMs（5个商业模型，18个开源模型）的评估显示，这些模型在动态视觉场景理解和跨模态干扰韧性方面存在显著的局限性。开源视频LLMs偶尔在真实性上表现更佳，但整体可信度不如商业模型，数据多样性比规模效应更具优势。这些发现凸显了提升模型能力需要先进的安全对齐方法。Trust-videoLLMs提供了一个公开可用、可扩展的工具箱，用于标准化的可信度评估，填补了以准确性为导向的基准测试与对鲁棒性、安全性、公平性和隐私性的关键需求之间的空白。

> Recent advancements in multimodal large language models for video understanding (videoLLMs) have improved their ability to process dynamic multimodal data. However, trustworthiness challenges factual inaccuracies, harmful content, biases, hallucinations, and privacy risks, undermine reliability due to video data's spatiotemporal complexities. This study introduces Trust-videoLLMs, a comprehensive benchmark evaluating videoLLMs across five dimensions: truthfulness, safety, robustness, fairness, and privacy. Comprising 30 tasks with adapted, synthetic, and annotated videos, the framework assesses dynamic visual scenarios, cross-modal interactions, and real-world safety concerns. Our evaluation of 23 state-of-the-art videoLLMs (5 commercial,18 open-source) reveals significant limitations in dynamic visual scene understanding and cross-modal perturbation resilience. Open-source videoLLMs show occasional truthfulness advantages but inferior overall credibility compared to commercial models, with data diversity outperforming scale effects. These findings highlight the need for advanced safety alignment to enhance capabilities. Trust-videoLLMs provides a publicly available, extensible toolbox for standardized trustworthiness assessments, bridging the gap between accuracy-focused benchmarks and critical demands for robustness, safety, fairness, and privacy.

[Arxiv](https://arxiv.org/abs/2506.12336)