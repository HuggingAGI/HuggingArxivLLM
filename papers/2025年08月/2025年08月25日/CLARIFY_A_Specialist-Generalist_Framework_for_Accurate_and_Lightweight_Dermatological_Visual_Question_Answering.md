# CLARIFY：面向准确轻量皮肤科视觉问答的专家-通才框架

发布时间：2025年08月25日

`LLM应用` `医疗健康`

> CLARIFY: A Specialist-Generalist Framework for Accurate and Lightweight Dermatological Visual Question Answering

# 摘要

> 视觉语言模型（VLMs）在医疗领域潜力巨大；但由于其通用性，专业诊断精度可能受限，且模型规模庞大，导致实际临床部署时推理成本居高不下。为应对这些问题，我们提出CLARIFY——一个面向皮肤科视觉问答（VQA）的“专家-通才”框架。CLARIFY整合了两大核心组件：（i）轻量级领域训练图像分类器（即“专家”），可快速输出高精度诊断预测；（ii）性能强大且经过压缩的对话式VLM（即“通才”），能为用户提问生成自然语言解释。在框架中，“专家”的预测结果直接引导“通才”的推理过程，使其专注于正确的诊断方向。这一协同机制通过知识图谱检索模块进一步强化——该模块将“通才”的回答锚定在皮肤科事实知识上，从而保证准确性与可靠性。这种分层设计不仅降低了诊断误差，还大幅提升了计算效率。在我们构建的多模态皮肤科数据集上的实验显示，CLARIFY的诊断准确率较最强基线（一个经微调的未压缩单行VLM）提升了18%，同时平均显存占用和延迟分别降低至少20%和5%。这些结果证实，“专家-通才”系统为构建轻量、可信且具备临床实用性的AI系统提供了一种实用高效的范式。

> Vision-language models (VLMs) have shown significant potential for medical tasks; however, their general-purpose nature can limit specialized diagnostic accuracy, and their large size poses substantial inference costs for real-world clinical deployment. To address these challenges, we introduce CLARIFY, a Specialist-Generalist framework for dermatological visual question answering (VQA). CLARIFY combines two components: (i) a lightweight, domain-trained image classifier (the Specialist) that provides fast and highly accurate diagnostic predictions, and (ii) a powerful yet compressed conversational VLM (the Generalist) that generates natural language explanations to user queries. In our framework, the Specialist's predictions directly guide the Generalist's reasoning, focusing it on the correct diagnostic path. This synergy is further enhanced by a knowledge graph-based retrieval module, which grounds the Generalist's responses in factual dermatological knowledge, ensuring both accuracy and reliability. This hierarchical design not only reduces diagnostic errors but also significantly improves computational efficiency. Experiments on our curated multimodal dermatology dataset demonstrate that CLARIFY achieves an 18\% improvement in diagnostic accuracy over the strongest baseline, a fine-tuned, uncompressed single-line VLM, while reducing the average VRAM requirement and latency by at least 20\% and 5\%, respectively. These results indicate that a Specialist-Generalist system provides a practical and powerful paradigm for building lightweight, trustworthy, and clinically viable AI systems.

[Arxiv](https://arxiv.org/abs/2508.18430)