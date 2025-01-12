# ECBench: 多模态基础模型能否理解自我中心的世界？一个全面的具身认知基准

发布时间：2025年01月09日

`Agent

理由：这篇论文主要讨论了大型视觉语言模型（LVLMs）在机器人具身认知能力方面的应用，特别是通过ECBench基准来评估和提升这些模型的具身认知能力。论文的核心内容围绕如何利用LVLMs来增强机器人的自我认知、动态场景感知等能力，这与Agent（智能体）的研究和应用密切相关。因此，这篇论文应归类为Agent。` `机器人` `认知评估`

> ECBench: Can Multi-modal Foundation Models Understand the Egocentric World? A Holistic Embodied Cognition Benchmark

# 摘要

> 大型视觉语言模型（LVLMs）在提升机器人泛化能力方面的作用日益显著，尤其是基于第一人称视频的具身认知能力备受关注。然而，现有具身视频问答数据集缺乏全面系统的评估框架，机器人自我认知、动态场景感知和幻觉等关键问题鲜有涉及。为此，我们提出了ECBench，一个高质量的基准，旨在系统评估LVLMs的具身认知能力。ECBench囊括多样化的场景视频、开放灵活的问题格式，以及30个维度的具身认知评估。为确保数据质量、平衡性和高视觉依赖性，ECBench采用类别无关的精细人工标注和多轮问题筛选策略。此外，我们引入了ECEval评估系统，确保指标公平合理。基于ECBench，我们对专有、开源及任务特定的LVLMs进行了广泛评估。ECBench在推动LVLMs具身认知能力方面具有重要意义，为开发可靠的具身代理核心模型奠定了坚实基础。所有数据和代码可在https://github.com/Rh-Dang/ECBench获取。

> The enhancement of generalization in robots by large vision-language models (LVLMs) is increasingly evident. Therefore, the embodied cognitive abilities of LVLMs based on egocentric videos are of great interest. However, current datasets for embodied video question answering lack comprehensive and systematic evaluation frameworks. Critical embodied cognitive issues, such as robotic self-cognition, dynamic scene perception, and hallucination, are rarely addressed. To tackle these challenges, we propose ECBench, a high-quality benchmark designed to systematically evaluate the embodied cognitive abilities of LVLMs. ECBench features a diverse range of scene video sources, open and varied question formats, and 30 dimensions of embodied cognition. To ensure quality, balance, and high visual dependence, ECBench uses class-independent meticulous human annotation and multi-round question screening strategies. Additionally, we introduce ECEval, a comprehensive evaluation system that ensures the fairness and rationality of the indicators. Utilizing ECBench, we conduct extensive evaluations of proprietary, open-source, and task-specific LVLMs. ECBench is pivotal in advancing the embodied cognitive capabilities of LVLMs, laying a solid foundation for developing reliable core models for embodied agents. All data and code are available at https://github.com/Rh-Dang/ECBench.

[Arxiv](https://arxiv.org/abs/2501.05031)