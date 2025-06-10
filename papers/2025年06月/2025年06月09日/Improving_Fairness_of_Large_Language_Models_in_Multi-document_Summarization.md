# # 提升大型语言模型在多文档摘要任务中的公平性

发布时间：2025年06月09日

`LLM应用` `公平性评估`

> Improving Fairness of Large Language Models in Multi-document Summarization

# 摘要

> 多文档摘要中的公平性对于提供全面观点至关重要，尤其是在处理具有不同社会属性值的文档时，这对决策有着重要影响。例如，若摘要系统倾向于过多呈现负面的产品评论，可能会误导消费者忽视优质产品。此前的研究在两个层面衡量多文档摘要的公平性：摘要层面和语料库层面。摘要层面的公平性关注单个摘要，而语料库层面的公平性则关注多个摘要的整体。近期研究主要聚焦于摘要层面的公平性。为此，我们提出了FairPO，一种同时兼顾摘要层面和语料库层面公平性的偏好调整方法。为提升摘要层面的公平性，我们建议通过扰动文档集来生成偏好对。为提升语料库层面的公平性，我们提出了一种动态调整偏好对权重的公平感知偏好调整方法。实验结果表明，FairPO在保持摘要关键质量的同时，超越了现有强大的基线方法。代码可访问：https://github.com/leehaoyuan/coverage_fairnes。

> Fairness in multi-document summarization (MDS) is crucial for providing comprehensive views across documents with diverse social attribute values, which can significantly impact decision-making. For example, a summarization system that tends to overrepresent negative reviews of products can mislead customers into disregarding good products. Previous works measure fairness in MDS at two levels: summary-level and corpus-level. While summary-level fairness focuses on individual summaries, corpus-level fairness focuses on a corpus of summaries. Recent methods primarily focus on summary-level fairness. We propose FairPO, a preference tuning method that focuses on both summary-level and corpus-level fairness in MDS. To improve summary-level fairness, we propose to generate preference pairs by perturbing document sets. To improve corpus-level fairness, we propose fairness-aware preference tuning by dynamically adjusting the weights of preference pairs. Our experiments show that FairPO outperforms strong baselines while maintaining the critical qualities of summaries. The code is available at https://github.com/leehaoyuan/coverage_fairnes.

[Arxiv](https://arxiv.org/abs/2506.07479)