# 突破传统算法：借助LLMs实现精准跨境实体识别

发布时间：2025年07月15日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在实体识别和分类任务中的应用，特别是在金融领域。它比较了传统方法与基于LLMs的方法，并展示了LLMs在处理复杂实体匹配问题中的优势。因此，它属于LLM应用类别。` `金融风险管理`

> Beyond Traditional Algorithms: Leveraging LLMs for Accurate Cross-Border Entity Identification

# 摘要

> 跨境金融活动的激增凸显了准确识别和分类外国实体的重要性，这一实践在西班牙金融体系中尤为关键，有助于提升风险管理、监管合规和防范金融违规行为。该流程涉及劳动密集型的实体匹配任务，需将实体与参考来源进行比对。然而，语言变体、特殊字符、过时名称及法律形式变化等因素，使传统匹配算法（如Jaccard、余弦和Levenshtein距离）面临挑战，难以准确捕捉上下文和语义关系。为解决这一难题，我们探索了大型语言模型（LLMs）作为灵活替代方案。LLMs通过广泛训练，能够理解上下文、处理缩写并适应法律变化。我们采用包含65个葡萄牙公司案例的数据集，对比了传统方法、基于Hugging Face的LLMs以及基于界面的LLMs（如Microsoft Copilot、阿里巴巴的Qwen 2.5）。结果显示，传统方法虽能达到92%以上的准确率，但误报率较高（20-40%）。相比之下，基于界面的LLMs表现更优，准确率超过93%，F1分数超过96%，误报率显著降低（40-80%）。

> The growing prevalence of cross-border financial activities in global markets has underscored the necessity of accurately identifying and classifying foreign entities. This practice is essential within the Spanish financial system for ensuring robust risk management, regulatory adherence, and the prevention of financial misconduct. This process involves a labor-intensive entity-matching task, where entities need to be validated against available reference sources. Challenges arise from linguistic variations, special characters, outdated names, and changes in legal forms, complicating traditional matching algorithms like Jaccard, cosine, and Levenshtein distances. These methods struggle with contextual nuances and semantic relationships, leading to mismatches. To address these limitations, we explore Large Language Models (LLMs) as a flexible alternative. LLMs leverage extensive training to interpret context, handle abbreviations, and adapt to legal transitions. We evaluate traditional methods, Hugging Face-based LLMs, and interface-based LLMs (e.g., Microsoft Copilot, Alibaba's Qwen 2.5) using a dataset of 65 Portuguese company cases. Results show traditional methods achieve accuracies over 92% but suffer high false positive rates (20-40%). Interface-based LLMs outperform, achieving accuracies above 93%, F1 scores exceeding 96%, and lower false positives (40-80%).

[Arxiv](https://arxiv.org/abs/2507.11086)