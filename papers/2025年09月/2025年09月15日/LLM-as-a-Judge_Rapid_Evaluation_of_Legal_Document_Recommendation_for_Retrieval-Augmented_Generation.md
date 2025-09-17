# LLM法官：面向检索增强生成的法律文档推荐快速评估

发布时间：2025年09月15日

`LLM应用` `法律科技`

> LLM-as-a-Judge: Rapid Evaluation of Legal Document Recommendation for Retrieval-Augmented Generation

# 摘要

> 随着生成式AI的崛起，推荐系统的评估瓶颈愈发突出——传统指标难以捕捉专业领域（如法律研究）中至关重要的细微质量维度。我们能否信任大型语言模型为同类生成内容担任可靠裁判？本文探索将LLM作为评判者（LLM-as-a-Judge）的规范化评估方法，聚焦法律场景下的检索增强生成系统（此类场景中推荐质量的重要性极高）。
  研究围绕两个决定实际可行性的核心问题展开：哪些评分者间信度指标最能体现LLM评估与人类判断的一致性？如何对竞争系统进行统计有效的比较？通过系统实验发现，传统一致性指标（如Krippendorff's alpha）在AI系统评估常见的偏态分布中可能产生误导；相比之下，Gwet's AC2和等级相关系数是更稳健的裁判选择指标，而经Benjamini-Hochberg校正的Wilcoxon符号秩检验则为可靠的系统比较提供了必要的统计严谨性。
  研究成果为可扩展、低成本的评估提供了可行路径：既能满足法律应用对精确性的要求，又将以往人力密集的评估瓶颈转变为自动化且具备统计依据的评估框架。

> The evaluation bottleneck in recommendation systems has become particularly acute with the rise of Generative AI, where traditional metrics fall short of capturing nuanced quality dimensions that matter in specialized domains like legal research. Can we trust Large Language Models to serve as reliable judges of their own kind? This paper investigates LLM-as-a-Judge as a principled approach to evaluating Retrieval-Augmented Generation systems in legal contexts, where the stakes of recommendation quality are exceptionally high.
  We tackle two fundamental questions that determine practical viability: which inter-rater reliability metrics best capture the alignment between LLM and human assessments, and how do we conduct statistically sound comparisons between competing systems? Through systematic experimentation, we discover that traditional agreement metrics like Krippendorff's alpha can be misleading in the skewed distributions typical of AI system evaluations. Instead, Gwet's AC2 and rank correlation coefficients emerge as more robust indicators for judge selection, while the Wilcoxon Signed-Rank Test with Benjamini-Hochberg corrections provides the statistical rigor needed for reliable system comparisons.
  Our findings suggest a path toward scalable, cost-effective evaluation that maintains the precision demanded by legal applications, transforming what was once a human-intensive bottleneck into an automated, yet statistically principled, evaluation framework.

[Arxiv](https://arxiv.org/abs/2509.12382)