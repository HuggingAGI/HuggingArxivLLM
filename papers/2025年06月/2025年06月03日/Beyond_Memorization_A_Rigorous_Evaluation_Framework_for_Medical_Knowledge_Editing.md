# # 突破死记硬背：构建医学知识编辑的严谨评估体系

发布时间：2025年06月03日

`LLM应用` `知识编辑`

> Beyond Memorization: A Rigorous Evaluation Framework for Medical Knowledge Editing

# 摘要

> 近年来，知识编辑（KE）作为一种无需完整重新训练即可更新大型语言模型（LLMs）特定事实的有前途方法，受到了广泛关注。尽管在通用领域基准测试中表现出色，但其在复杂医疗领域的应用潜力仍待挖掘。医疗知识编辑面临独特挑战，要求LLMs不仅能够内化知识，还需在未见场景中实现有效且可解释的决策。为此，我们提出了MedEditBench框架，旨在全面评估现有KE方法在医疗领域的实际效果。MedEditBench不仅引入了全新的医疗知识编辑基准，还设计了三种不同的知识编辑范式，用于探究不同知识来源在编辑过程中的作用。研究发现表明，现有KE方法仅能实现注入信息的浅层记忆，缺乏对新场景的推广能力。为解决这一问题，我们提出了自我生成理由编辑（SGR-Edit），该方法通过利用模型生成的理由作为目标知识，揭示了模型的内在推理过程，并显著超越了现有KE方法的性能。此外，本研究还深入探讨了医疗知识编辑中的关键问题，包括医疗知识在LLMs中的定位机制，以及顺序编辑对知识演进的影响。这些发现为在实际医疗场景中应用KE方法提供了宝贵的实践指导。

> Recently, knowledge editing (KE) has emerged as a promising approach to update specific facts in Large Language Models (LLMs) without the need for full retraining. Despite the effectiveness in general-domain benchmarks, their applicability to complex medical domain remains largely unexplored. Medical knowledge editing is particularly challenging, as it requires LLMs to internalize the knowledge and generalize to unseen scenarios for effective and interpretable decision-making. In this work, we propose a novel framework called MedEditBench to rigorously evaluate the effectiveness of existing KE methods in the medical domain. In MedEditBench, we introduce a new medical knowledge editing benchmark as well as three different knowledge editing paradigms, which are designed to assess the impact of different knowledge sources for editing. Our findings indicate that current KE methods result in only superficial memorization of the injected information, failing to generalize to new scenarios. To overcome this limitation, we present Self-Generated Rationale Editing (SGR-Edit), which utilizes model-derived rationales as the target knowledge for editing, thereby uncovering the underlying reasoning process and demonstrating significant improvements over existing KE approaches. Additionally, we offer deeper insights into medical knowledge editing, including the localization of medical knowledge in LLMs and the impact of sequential editing on evolving knowledge. This could provide practical guidance for implementing KE methods in real-world medical applications.

[Arxiv](https://arxiv.org/abs/2506.03490)