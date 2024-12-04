# 让专家参与其中：利用大型语言模型实现临床数据分类的专家引导式优化

发布时间：2024年12月03日

`LLM应用` `语言模型`

> Keeping Experts in the Loop: Expert-Guided Optimization for Clinical Data Classification using Large Language Models

# 摘要

> 自大型语言模型（LLMs）问世以来，如何在医疗保健领域有效发挥其潜力这一挑战备受关注。利用LLMs从非结构化临床笔记中提取见解的关键阻碍在于提示工程流程。尽管其在决定任务表现方面至关重要，但明确的提示优化框架仍缺失。当前弥补这一差距的方法，要么是手动提示改进，即领域专家与提示工程师合作创建最优提示，此方法耗时且难以规模化；要么是采用自动提示优化，然而这类方法未能充分发挥领域专家输入的价值。为此，我们提出StructEase，这一全新框架弥合了提示工程中自动化与人类专业知识输入之间的鸿沟。框架的核心创新在于SamplEase，这是一种迭代采样算法，能识别出专家反馈可大幅提升性能的高价值案例。该方法最大程度减少了专家干预，有效提升了分类结果。这种针对性策略减少了标记冗余，降低了人为错误，提高了分类效果。我们使用来自美国国家电子伤害监测系统（NEISS）的去识别临床叙述数据集对StructEase的性能进行了评估，与现有方法相比，其在分类性能上有显著提升。我们的发现突显了专家整合在LLM工作流中的价值，在保持专家投入最小化的同时显著提高了F1分数。通过融合透明度、灵活性和可扩展性，StructEase为在医疗保健及其他领域将专家输入融入LLM工作流的框架奠定了基础。

> Since the emergence of Large Language Models (LLMs), the challenge of effectively leveraging their potential in healthcare has taken center stage. A critical barrier to using LLMs for extracting insights from unstructured clinical notes lies in the prompt engineering process. Despite its pivotal role in determining task performance, a clear framework for prompt optimization remains absent. Current methods to address this gap take either a manual prompt refinement approach, where domain experts collaborate with prompt engineers to create an optimal prompt, which is time-intensive and difficult to scale, or through employing automatic prompt optimizing approaches, where the value of the input of domain experts is not fully realized. To address this, we propose StructEase, a novel framework that bridges the gap between automation and the input of human expertise in prompt engineering. A core innovation of the framework is SamplEase, an iterative sampling algorithm that identifies high-value cases where expert feedback drives significant performance improvements. This approach minimizes expert intervention, to effectively enhance classification outcomes. This targeted approach reduces labeling redundancy, mitigates human error, and enhances classification outcomes. We evaluated the performance of StructEase using a dataset of de-identified clinical narratives from the US National Electronic Injury Surveillance System (NEISS), demonstrating significant gains in classification performance compared to current methods. Our findings underscore the value of expert integration in LLM workflows, achieving notable improvements in F1 score while maintaining minimal expert effort. By combining transparency, flexibility, and scalability, StructEase sets the foundation for a framework to integrate expert input into LLM workflows in healthcare and beyond.

[Arxiv](https://arxiv.org/abs/2412.02173)