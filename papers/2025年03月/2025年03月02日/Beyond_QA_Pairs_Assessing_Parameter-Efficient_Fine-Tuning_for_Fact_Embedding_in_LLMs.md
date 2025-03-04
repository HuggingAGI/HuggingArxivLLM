# # 超越问答对：深入探讨 LLMs 中事实嵌入的参数高效微调方法

发布时间：2025年03月02日

`LLM应用` `数据中心`

> Beyond QA Pairs: Assessing Parameter-Efficient Fine-Tuning for Fact Embedding in LLMs

# 摘要

> 本文全面研究了将领域特定知识嵌入大型语言模型（LLMs）的参数高效微调方法（PEFT），通过使用基于BERT的分类器将问答对（QA）分为事实类和概念类，进而优化微调流程。我们基于这些分类对两个不同的Llama-2模型进行了微调，并使用GPT-3.5 Turbo和Gemini等更大规模的模型进行评估。研究结果显示，基于概念类数据集训练的模型表现优于基于事实类数据集训练的模型。此外，我们对比了两种合成微调数据集生成技术（D-RAG和D-Naive）的效率，结果表明D-Naive表现更优。尽管PEFT已展现出有效性，但我们的研究发现它可能并非将事实嵌入LLMs的最优方法。然而，它在基于指令的任务中表现尤为出色。我们的结论得到了数据中心领域1000样本数据集的验证，其中微调后的Llama-2 7B模型在生成产品推荐方面显著优于基线模型。本研究强调了问答对分类和合成数据集生成技术在提升LLMs领域特定性能中的重要性。

> This paper presents an extensive examination of Parameter-Efficient Fine-Tuning (PEFT) for embedding domain specific facts into Large Language Models (LLMs), focusing on improving the fine-tuning process by categorizing question-answer (QA) pairs into Factual and Conceptual classes using a BERT-based classifier. Two distinct Llama-2 models are fine-tuned based on these classifications and evaluated using larger models like GPT-3.5 Turbo and Gemini. Our results indicate that models trained on conceptual datasets outperform those trained on factual datasets. Additionally, we compare the efficiency of two synthetic fine-tuning dataset generation techniques, D-RAG and D-Naive, with D-Naive demonstrating superior performance. Although PEFT has shown effectiveness, our research indicates that it may not be the most optimal method for embedding facts into LLMs. However, it has demonstrated exceptional performance in instruction-based tasks. Our findings are reinforced by a 1000-sample dataset in the data center domain, where the fine-tuned Llama-2 7B model significantly outperforms the baseline model in generating product recommendations. Our study highlights the importance of QA pair categorization and synthetic dataset generation techniques in enhancing the performance of LLMs in specific domains.

[Arxiv](https://arxiv.org/abs/2503.01131)