# 基于LLM的食品安全法规需求条款分类实证研究

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要探讨了如何使用BERT和GPT等大型语言模型（LLMs）来自动分类食品安全法规中的法律条款。研究重点在于评估这些模型在特定任务中的表现，并比较了不同模型（如BERT和GPT-4o）的性能。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `食品安全`

> An Empirical Study on LLM-based Classification of Requirements-related Provisions in Food-safety Regulations

# 摘要

> 随着工业4.0重塑食品行业，软件在确保食品安全法规合规方面的作用日益重要。食品安全法规，如同许多法律领域，通常以技术无关的方式表述，以确保其长期适用性。然而，这种方式在法规与现代系统和软件之间形成了鸿沟。本文旨在实现两个目标：首先，通过扎根理论研究食品安全法规，构建与系统和软件需求紧密相关的食品安全概念框架；其次，评估BERT和GPT两类大型语言模型（LLMs）在基于食品安全概念自动分类法律条款中的表现。研究结果显示：（a）微调后，BERT和GPT家族中表现最佳的模型准确率差异较小，但GPT-4o仍以89%的平均精确率和87%的平均召回率领先；（b）使用GPT-4o进行少样本学习可将召回率提升至97%，但精确率降至65%，表明微调与少样本学习之间存在权衡；（c）尽管训练数据仅来自加拿大法规，LLM在美国法规测试中表现稳定，展现了跨监管辖区的泛化能力；（d）在分类任务中，LLMs显著优于基于LSTM网络和自动关键词提取的简单基线模型。

> As Industry 4.0 transforms the food industry, the role of software in achieving compliance with food-safety regulations is becoming increasingly critical. Food-safety regulations, like those in many legal domains, have largely been articulated in a technology-independent manner to ensure their longevity and broad applicability. However, this approach leaves a gap between the regulations and the modern systems and software increasingly used to implement them. In this article, we pursue two main goals. First, we conduct a Grounded Theory study of food-safety regulations and develop a conceptual characterization of food-safety concepts that closely relate to systems and software requirements. Second, we examine the effectiveness of two families of large language models (LLMs) -- BERT and GPT -- in automatically classifying legal provisions based on requirements-related food-safety concepts. Our results show that: (a) when fine-tuned, the accuracy differences between the best-performing models in the BERT and GPT families are relatively small. Nevertheless, the most powerful model in our experiments, GPT-4o, still achieves the highest accuracy, with an average Precision of 89% and an average Recall of 87%; (b) few-shot learning with GPT-4o increases Recall to 97% but decreases Precision to 65%, suggesting a trade-off between fine-tuning and few-shot learning; (c) despite our training examples being drawn exclusively from Canadian regulations, LLM-based classification performs consistently well on test provisions from the US, indicating a degree of generalizability across regulatory jurisdictions; and (d) for our classification task, LLMs significantly outperform simpler baselines constructed using long short-term memory (LSTM) networks and automatic keyword extraction.

[Arxiv](https://arxiv.org/abs/2501.14683)