# # 你当时在想什么？基于LLM的开源项目重构动机大规模研究

发布时间：2025年09月09日

`LLM应用` `基础理论`

> What Were You Thinking? An LLM-Driven Large-Scale Study of Refactoring Motivations in Open-Source Projects

# 摘要

> Context. 代码重构能在不改变外部行为的前提下提升软件质量。尽管优势显著，但其高昂的时间、资源成本及持续投入需求，却制约了实际效益的发挥。
Aim. 若能厘清开发人员的重构动因，明确哪些指标可捕捉这些动机，将有助于在实践中更广泛、更高效地运用重构。
Method. 我们开展了大规模实证研究，分析开发人员的重构行为：借助大型语言模型（LLMs）从版本控制数据中识别深层动机，并将研究发现与文献中已有的重构动机进行对比。
Results. 研究结果显示：LLMs的判断与人类判断在80%的案例中一致，但与文献记载的动机仅47%吻合；它们为22%的动机补充了更详尽的理由，常突出可读性、清晰度及结构优化的需求。多数动机具有务实性，聚焦于简化代码和提升可维护性。尽管与开发人员经验、代码可读性相关的指标排名最高，但这些指标与动机类别的相关性较弱。
Conclusions. 结论表明：LLMs能有效捕捉表层动机，但在架构层面的推理能力较弱；其价值在于提供局部化解释，与软件指标结合后可形成混合方法。这种融合为更系统地确定重构优先级、平衡短期改进与长期架构目标开辟了新的可能。

> Context. Code refactoring improves software quality without changing external behavior. Despite its advantages, its benefits are hindered by the considerable cost of time, resources, and continuous effort it demands. Aim. Understanding why developers refactor, and which metrics capture these motivations, may support wider and more effective use of refactoring in practice. Method. We performed a large-scale empirical study to analyze developers refactoring activity, leveraging Large Language Models (LLMs) to identify underlying motivations from version control data, comparing our findings with previous motivations reported in the literature. Results. LLMs matched human judgment in 80% of cases, but aligned with literature-based motivations in only 47%. They enriched 22% of motivations with more detailed rationale, often highlighting readability, clarity, and structural improvements. Most motivations were pragmatic, focused on simplification and maintainability. While metrics related to developer experience and code readability ranked highest, their correlation with motivation categories was weak. Conclusions. We conclude that LLMs effectively capture surface-level motivations but struggle with architectural reasoning. Their value lies in providing localized explanations, which, when combined with software metrics, can form hybrid approaches. Such integration offers a promising path toward prioritizing refactoring more systematically and balancing short-term improvements with long-term architectural goals.

[Arxiv](https://arxiv.org/abs/2509.07763)