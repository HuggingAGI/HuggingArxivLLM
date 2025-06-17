# # 设计面向 LLM 的深度学习框架：机遇、挑战与未来展望

发布时间：2025年06月16日

`其他` `工业应用`

> Designing Deep Learning Frameworks for LLMs:Challenges, Expectations, and Opportunities

# 摘要

> 大型语言模型 (LLMs) 在实际工业应用中取得了重大突破，但其高效构建、分布式执行和优化部署都离不开深度学习 (DL) 框架的支持。然而，LLMs 巨大的参数规模和漫长的执行周期对 DL 框架的可扩展性、稳定性和效率提出了极高要求。当前，DL 框架中普遍存在的较差易用性、有限功能以及隐蔽 bug 可能严重阻碍开发效率，导致系统故障或资源浪费。尽管如此，一个关键问题仍未得到充分研究：DL 框架在支持 LLMs 时面临哪些挑战？

为解答这一问题，我们从三大主流 DL 框架（MindSpore、PyTorch、TensorFlow）及其相关八个 LLM 工具包（如 Megatron）中收集并分析了大量问题报告。通过构建以 LLM 为中心的 bug、需求和用户问题分类体系，并结合 11 名 LLM 用户和 8 名 DL 框架开发者的深度访谈，我们揭示了当前技术的主要挑战以及用户需求与开发者优先级之间的不匹配。

我们的研究贡献包括：(1) 构建了一个全面的分类体系，涵盖四个问题主题（九个子主题）、四个需求主题（15 个子主题）和十个 bug 主题（45 个子主题）；(2) 根据从业者见解评估了各项挑战的重要性和优先级；(3) 在 LLM 开发领域发现了五个关键问题，并提出了五项具体建议，以提升 DL 框架的可靠性、易用性和可测试性。研究结果不仅揭示了当前 DL 框架的关键局限，更为下一代 LLM 的构建和应用提供了切实可行的改进方向。

> Large language models (LLMs) drive significant advancements in real industry applications. LLMs rely on DL frameworks for efficient model construction, distributed execution, and optimized deployment. Their large parameter scale and long execution cycles place extreme demands on DL frameworks in terms of scalability, stability, and efficiency. Therefore, poor usability, limited functionality, and subtle bugs in DL frameworks may hinder development efficiency and cause severe failures or resource waste. However, a fundamental question remains underinvestigated, i.e., What challenges do DL frameworks face in supporting LLMs? To seek an answer, we investigate these challenges through a large-scale analysis of issue reports from three major DL frameworks (MindSpore, PyTorch, TensorFlow) and eight associated LLM toolkits (e.g., Megatron). We construct a taxonomy of LLM-centric bugs, requirements, and user questions and enrich it through interviews with 11 LLM users and eight DL framework developers, uncovering key technical challenges and misalignments between user needs and developer priorities. Our contributions are threefold: (1) we develop a comprehensive taxonomy comprising four question themes (nine sub-themes), four requirement themes (15 sub-themes), and ten bug themes (45 sub-themes); (2) we assess the perceived importance and priority of these challenges based on practitioner insights; and (3) we identify five key findings across the LLM development and propose five actionable recommendations to improve the reliability, usability, and testability of DL frameworks. Our results highlight critical limitations in current DL frameworks and offer concrete guidance for advancing their support for the next generation of LLM construction and applications.

[Arxiv](https://arxiv.org/abs/2506.13114)