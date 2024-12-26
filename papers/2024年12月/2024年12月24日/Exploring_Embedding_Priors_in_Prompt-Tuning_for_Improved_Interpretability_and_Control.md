# 探索提示调整中的嵌入先验，以提升可解释性与控制能力

发布时间：2024年12月24日

`LLM应用` `人工智能`

> Exploring Embedding Priors in Prompt-Tuning for Improved Interpretability and Control

# 摘要

> 提示调整是一种能让预训练语言模型以极小的计算成本适应新任务的高效方法，只需修改提示嵌入即可。在本研究中，我们探究了提示调整中常见的嵌入崩溃现象对模型最终性能的关键程度。为解决此问题，我们设计了嵌入先验，并与收敛的软和深度提示调整方法的后验进行对比。我们发现，先验对调整后的嵌入位置影响显著，模型能有效使用激活空间不同部位的嵌入，甚至包括全新区域。鉴于最终的提示调整能力有限，我们推测可控的提示调整后验或许能成为诸如思维链提炼等任务的良好开端。我们的实验还显示，生成的轨迹并非局限于模型的激活空间。不过，不同的任务（如 NLP 和算术）存在明显的激活簇，而 NLP 任务（如问答和 MLM）之间的激活处于同一簇中。这些观察结果让人思考单个激活簇对于大型语言模型泛化能力的重要性。

> Prompt-Tuning is an efficient method for adapting pre-trained language models to new tasks with minimal computational overhead by modifying prompt embeddings. In this work, we investigate how crucial the phenomenon of embedding collapse, frequently observed in Prompt-Tuning, is for the final performance of the model. To address this question, we designed embedding priors and compared them with posteriors of the converged Soft and Deep Prompt-Tuning methods. Our findings suggest that priors strongly affect the position of the tuned embeddings, and models can effectively work with embeddings from different parts of activation spaces, including completely new regions. As the final Prompt-Tuning capabilities are limited, we hypothesize that controllable Prompt-Tuning posteriors may serve as a good starting point for tasks such as chain-of-thought (COT) distillation. Our experiments also show that generated trajectories are not localized in the activation space of the models. However, there are distinct clusters of activations for distant tasks (e.g., NLP and arithmetic), while activations between NLP tasks (e.g., Question-Answering and MLM) lie in the same cluster. These observations raise questions about the importance of a single activation cluster for the generalization abilities of large language models.

[Arxiv](https://arxiv.org/abs/2412.18582)