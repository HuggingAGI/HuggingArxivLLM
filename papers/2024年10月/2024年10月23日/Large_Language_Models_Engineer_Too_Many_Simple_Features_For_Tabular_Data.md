# 大型语言模型为表格数据生成了过多的简单特征

发布时间：2024年10月23日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在特征工程中的应用，特别是LLMs在生成新特征时可能存在的偏见问题。虽然涉及到了LLMs的潜在偏见，但核心内容仍然是关于如何利用LLMs进行自动化数据科学任务（如特征工程），因此应归类为LLM应用。` `机器学习` `数据科学`

> Large Language Models Engineer Too Many Simple Features For Tabular Data

# 摘要

> # 摘要
表格机器学习问题通常需要耗费大量时间和精力的特征工程。最近的研究聚焦于利用大型语言模型（LLMs）来挖掘其潜在的领域知识。然而，研究人员在其他LLM相关应用中（如文本生成）发现了伦理上令人担忧的负面偏见。这促使我们探讨LLMs是否在特征工程中存在偏见，从而影响性能。虽然这种偏见不涉及伦理问题，但它可能阻碍从业者充分利用LLMs进行自动化数据科学。为此，我们提出了一种方法，通过检测LLMs在生成新特征时推荐的操作符（如加法）频率异常来识别潜在偏见。我们评估了四种LLMs（两种大型前沿模型和两种小型开源模型）在27个表格数据集上的表现。结果显示，LLMs倾向于使用简单操作符（如加法），而忽略了更复杂的操作符（如分组后聚合）。这种偏见可能会降低使用LLM生成特征的预测性能。因此，我们呼吁在使用LLMs进行特征工程时采取措施减轻偏见。

> Tabular machine learning problems often require time-consuming and labor-intensive feature engineering. Recent efforts have focused on using large language models (LLMs) to capitalize on their potential domain knowledge. At the same time, researchers have observed ethically concerning negative biases in other LLM-related use cases, such as text generation. These developments motivated us to investigate whether LLMs exhibit a bias that negatively impacts the performance of feature engineering. While not ethically concerning, such a bias could hinder practitioners from fully utilizing LLMs for automated data science. Therefore, we propose a method to detect potential biases by detecting anomalies in the frequency of operators (e.g., adding two features) suggested by LLMs when engineering new features. Our experiments evaluate the bias of four LLMs, two big frontier and two small open-source models, across 27 tabular datasets. Our results indicate that LLMs are biased toward simple operators, such as addition, and can fail to utilize more complex operators, such as grouping followed by aggregations. Furthermore, the bias can negatively impact the predictive performance when using LLM-generated features. Our results call for mitigating bias when using LLMs for feature engineering.

[Arxiv](https://arxiv.org/abs/2410.17787)