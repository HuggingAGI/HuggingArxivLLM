# 增强语言模型的稳健性，使其更好应对否定

发布时间：2025年02月11日

`LLM应用

理由：这篇论文讨论了语言模型在处理否定句方面的挑战，并提出了一种自监督方法来改进模型的处理能力。研究集中在模型的应用和改进上，属于LLM应用的范畴。` `问答系统`

> Making Language Models Robust Against Negation

# 摘要

> 否定句的理解一直是语言模型的难题。已有研究表明，语言模型在处理否定句时表现不佳，尤其在多种自然语言理解任务中尤为明显。针对这一问题，我们提出了一种自监督方法，旨在增强语言模型对否定句的处理能力。我们创新性地提出了下句情感预测任务（NSPP），并改进了传统的下句预测任务（NSP）。通过在BERT和RoBERTa模型上进行针对性预训练，我们在九个否定相关基准测试中取得了显著提升。其中，在大规模问答数据集CondaQA上，我们的方法带来了1.8%到9.1%的性能提升，这充分展示了在处理否定推理任务中的优势。

> Negation has been a long-standing challenge for language models. Previous studies have shown that they struggle with negation in many natural language understanding tasks. In this work, we propose a self-supervised method to make language models more robust against negation. We introduce a novel task, Next Sentence Polarity Prediction (NSPP), and a variation of the Next Sentence Prediction (NSP) task. We show that BERT and RoBERTa further pre-trained on our tasks outperform the off-the-shelf versions on nine negation-related benchmarks. Most notably, our pre-training tasks yield between 1.8% and 9.1% improvement on CondaQA, a large question-answering corpus requiring reasoning over negation.

[Arxiv](https://arxiv.org/abs/2502.07717)