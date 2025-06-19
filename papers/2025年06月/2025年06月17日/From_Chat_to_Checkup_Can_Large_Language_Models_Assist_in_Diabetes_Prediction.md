# 从闲聊到体检：大型语言模型能否助力糖尿病预测？

发布时间：2025年06月17日

`LLM应用`

> From Chat to Checkup: Can Large Language Models Assist in Diabetes Prediction?

# 摘要

> 尽管机器学习（ML）和深度学习（DL）模型在糖尿病预测中得到了广泛应用，但大型语言模型（LLMs）在结构化数值数据上的应用仍不成熟。本研究旨在测试LLMs在糖尿病预测中的有效性，采用零样本、一样本和三样本提示方法。我们使用Pima印度人糖尿病数据库（PIDD）进行实证分析，并评估了六种LLMs，包括开源模型：Gemma-2-27B、Mistral-7B、Llama-3.1-8B和Llama-3.2-2B，以及专有模型：GPT-4o和Gemini Flash 2.0。此外，我们将它们与三种传统机器学习模型：随机森林、逻辑回归和支持向量机（SVM）进行比较。我们采用准确率、精确率、召回率和F1值作为评估指标。结果显示，专有LLMs的表现优于开源模型，其中GPT-4o和Gemma-2-27B在少样本设置中达到了最高准确率。值得注意的是，Gemma-2-27B在F1值方面也优于传统ML模型。然而，仍存在一些问题，如不同提示策略下的性能波动以及对领域特定微调的需求。本研究表明，LLMs在医学预测任务中具有潜力，并鼓励未来在提示工程和混合方法方面进行研究，以改善医疗预测。

> While Machine Learning (ML) and Deep Learning (DL) models have been widely used for diabetes prediction, the use of Large Language Models (LLMs) for structured numerical data is still not well explored. In this study, we test the effectiveness of LLMs in predicting diabetes using zero-shot, one-shot, and three-shot prompting methods. We conduct an empirical analysis using the Pima Indian Diabetes Database (PIDD). We evaluate six LLMs, including four open-source models: Gemma-2-27B, Mistral-7B, Llama-3.1-8B, and Llama-3.2-2B. We also test two proprietary models: GPT-4o and Gemini Flash 2.0. In addition, we compare their performance with three traditional machine learning models: Random Forest, Logistic Regression, and Support Vector Machine (SVM). We use accuracy, precision, recall, and F1-score as evaluation metrics. Our results show that proprietary LLMs perform better than open-source ones, with GPT-4o and Gemma-2-27B achieving the highest accuracy in few-shot settings. Notably, Gemma-2-27B also outperforms the traditional ML models in terms of F1-score. However, there are still issues such as performance variation across prompting strategies and the need for domain-specific fine-tuning. This study shows that LLMs can be useful for medical prediction tasks and encourages future work on prompt engineering and hybrid approaches to improve healthcare predictions.

[Arxiv](https://arxiv.org/abs/2506.14949)