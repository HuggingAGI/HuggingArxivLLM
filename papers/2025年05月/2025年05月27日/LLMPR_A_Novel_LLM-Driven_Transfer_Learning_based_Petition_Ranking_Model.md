# LLMPR：基于LLM的迁移学习请愿排名新模型

发布时间：2025年05月27日

`LLM应用` `机器学习`

> LLMPR: A Novel LLM-Driven Transfer Learning based Petition Ranking Model

# 摘要

> 印度司法系统中未决案件的持续积累，尤其是印度司法体系内部，严重阻碍了正义的及时实现。手动处理请愿书的优先级排序往往效率低下且容易受主观偏见影响，进一步加剧了案件拖延。为了解决这一问题，我们提出了LLMPR（基于大型语言模型的请愿书排序框架），这是一个利用迁移学习和机器学习的自动化系统，根据案件的紧急程度为其分配优先级。我们借助包含7,593份标注请愿书的ILDC数据集，通过DistilBERT、LegalBERT和MiniLM等多种嵌入技术对非结构化的法律文本进行处理和特征提取。这些文本嵌入与案件搁置天数、排名分数和字数等定量指标相结合，用于训练包括随机森林、决策树、XGBoost、LightGBM和CatBoost在内的多种机器学习模型。实验结果表明，随机森林和决策树模型表现尤为突出，准确率超过99%，Spearman等级相关系数达到0.99。值得注意的是，仅使用数值特征的模型也取得了接近最优的排序效果（R2=0.988，ρ=0.998），而基于LLM的嵌入方法仅带来微小提升。这些发现表明，自动化的请愿书排序系统能够有效优化司法工作流程，减少案件积压，并提升案件优先级分配的公平性。

> The persistent accumulation of unresolved legal cases, especially within the Indian judiciary, significantly hampers the timely delivery of justice. Manual methods of prioritizing petitions are often prone to inefficiencies and subjective biases further exacerbating delays. To address this issue, we propose LLMPR (Large Language Model-based Petition Ranking), an automated framework that utilizes transfer learning and machine learning to assign priority rankings to legal petitions based on their contextual urgency. Leveraging the ILDC dataset comprising 7,593 annotated petitions, we process unstructured legal text and extract features through various embedding techniques, including DistilBERT, LegalBERT, and MiniLM. These textual embeddings are combined with quantitative indicators such as gap days, rank scores, and word counts to train multiple machine learning models, including Random Forest, Decision Tree, XGBoost, LightGBM, and CatBoost. Our experiments demonstrate that Random Forest and Decision Tree models yield superior performance, with accuracy exceeding 99% and a Spearman rank correlation of 0.99. Notably, models using only numerical features achieve nearly optimal ranking results (R2 = 0.988, \r{ho} = 0.998), while LLM-based embeddings offer only marginal gains. These findings suggest that automated petition ranking can effectively streamline judicial workflows, reduce case backlog, and improve fairness in legal prioritization.

[Arxiv](https://arxiv.org/abs/2505.21689)