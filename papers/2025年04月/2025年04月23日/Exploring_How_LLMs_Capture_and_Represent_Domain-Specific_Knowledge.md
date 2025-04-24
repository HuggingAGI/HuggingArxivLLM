# # 探索大型语言模型如何捕捉和表示领域特定知识

发布时间：2025年04月23日

`LLM理论

摘要中探讨了大型语言模型在特定领域中的表现和能力，研究了模型如何区分不同领域，以及模型选择和表示的鲁棒性。这些内容涉及模型的内在机制和理论分析，属于LLM理论类别。` `模型选择`

> Exploring How LLMs Capture and Represent Domain-Specific Knowledge

# 摘要

> 我们研究大型语言模型（LLMs）是否天生具备捕捉自然语言中特定领域细微差别的能力。通过实验，我们发现LLMs能够区分不同领域的查询，并且微调后的模型并不总是最准确的。与以往研究不同，我们的解释适用于闭合和开放式的生成任务。我们的方法利用这些表示进行模型选择，将输入查询的领域轨迹与最匹配的LLM进行映射（即在类似轨迹上表现最佳的模型）。我们发现了一些潜在的与领域相关的轨迹，这表明模型在内部识别查询所属的领域。我们还研究了这些领域表示在不同提示风格和来源下的鲁棒性。

> We study whether Large Language Models (LLMs) inherently capture domain-specific nuances in natural language. Our experiments probe the domain sensitivity of LLMs by examining their ability to distinguish queries from different domains using hidden states generated during the prefill phase. We reveal latent domain-related trajectories that indicate the model's internal recognition of query domains. We also study the robustness of these domain representations to variations in prompt styles and sources. Our approach leverages these representations for model selection, mapping the LLM that best matches the domain trace of the input query (i.e., the model with the highest performance on similar traces). Our findings show that LLMs can differentiate queries for related domains, and that the fine-tuned model is not always the most accurate. Unlike previous work, our interpretations apply to both closed and open-ended generative tasks

[Arxiv](https://arxiv.org/abs/2504.16871)