# CLARIFY：专家-通才融合框架——实现准确轻量的皮肤科视觉问答

发布时间：2025年08月25日

`LLM应用` `医疗健康`

> CLARIFY: A Specialist-Generalist Framework for Accurate and Lightweight Dermatological Visual Question Answering

# 摘要

> 视觉语言模型（VLMs）在医疗领域潜力巨大，但通用特性会限制专业诊断精度，且模型体积庞大，为实际临床部署带来高昂的推理成本。为应对这些挑战，我们推出CLARIFY——一个面向皮肤科视觉问答（VQA）的“专家-通才”框架。该框架整合两大核心组件：（i）轻量级领域训练图像分类器（专家），实现快速、高精度的诊断预测；（ii）性能强劲且经压缩的对话式VLM（通才），为用户查询生成自然语言解答。在框架中，专家的预测直接引导通才的推理过程，使其聚焦于正确的诊断方向。这一协同机制通过知识图谱检索模块得到进一步强化——该模块将通才的回答锚定在事实性皮肤病学知识上，从而保证准确性与可靠性。这种分层设计不仅降低了诊断误差，还大幅提升了计算效率。在我们精心构建的多模态皮肤病数据集上的实验显示，CLARIFY相较于最强基线（一个经微调、未压缩的单行VLM），诊断准确率提升18%，同时平均显存占用和延迟分别降低至少20%和5%。

> Vision-language models (VLMs) have shown significant potential for medical tasks; however, their general-purpose nature can limit specialized diagnostic accuracy, and their large size poses substantial inference costs for real-world clinical deployment. To address these challenges, we introduce CLARIFY, a Specialist-Generalist framework for dermatological visual question answering (VQA). CLARIFY combines two components: (i) a lightweight, domain-trained image classifier (the Specialist) that provides fast and highly accurate diagnostic predictions, and (ii) a powerful yet compressed conversational VLM (the Generalist) that generates natural language explanations to user queries. In our framework, the Specialist's predictions directly guide the Generalist's reasoning, focusing it on the correct diagnostic path. This synergy is further enhanced by a knowledge graph-based retrieval module, which grounds the Generalist's responses in factual dermatological knowledge, ensuring both accuracy and reliability. This hierarchical design not only reduces diagnostic errors but also significantly improves computational efficiency. Experiments on our curated multimodal dermatology dataset demonstrate that CLARIFY achieves an 18\% improvement in diagnostic accuracy over the strongest baseline, a fine-tuned, uncompressed single-line VLM, while reducing the average VRAM requirement and latency by at least 20\% and 5\%, respectively. These results indicate that a Specialist-Generalist system provides a practical and powerful paradigm for building lightweight, trustworthy, and clinically viable AI systems.

[Arxiv](https://arxiv.org/abs/2508.18430)