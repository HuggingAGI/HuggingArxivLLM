# BIS推理1.0：首个针对信念不一致三段论推理的大规模日语基准测试

发布时间：2025年06月07日

`LLM应用`

> BIS Reasoning 1.0: The First Large-Scale Japanese Benchmark for Belief-Inconsistent Syllogistic Reasoning

# 摘要

> 我们推出了 BIS Reasoning 1.0，这是首个专为评估大型语言模型 (LLMs) 中信念不一致推理能力而设计的大型日语三段论推理问题数据集。与专注于一般推理或信念一致推理的现有数据集（如 NeuBAROCO 和 JFLD）不同，BIS Reasoning 1.0 引入了逻辑上有效但信念不一致的三段论，以揭示在基于人类对齐语料库训练的 LLMs 中推理偏见。我们对当前最先进的模型（包括 GPT 模型、Claude 模型以及领先的日语 LLMs）进行了基准测试，结果显示性能存在显著差异，其中 GPT-4o 达到了 79.54% 的准确率。我们的分析揭示了当前 LLMs 在处理逻辑上有效但与信念冲突的输入时的关键弱点。这些发现对在法律、医疗和科学文献等高风险领域部署 LLMs 具有重要意义，因为在这些领域，事实真相必须超越直觉信念，以确保完整性和安全性。

> We present BIS Reasoning 1.0, the first large-scale Japanese dataset of syllogistic reasoning problems explicitly designed to evaluate belief-inconsistent reasoning in large language models (LLMs). Unlike prior datasets such as NeuBAROCO and JFLD, which focus on general or belief-aligned reasoning, BIS Reasoning 1.0 introduces logically valid yet belief-inconsistent syllogisms to uncover reasoning biases in LLMs trained on human-aligned corpora. We benchmark state-of-the-art models - including GPT models, Claude models, and leading Japanese LLMs - revealing significant variance in performance, with GPT-4o achieving 79.54% accuracy. Our analysis identifies critical weaknesses in current LLMs when handling logically valid but belief-conflicting inputs. These findings have important implications for deploying LLMs in high-stakes domains such as law, healthcare, and scientific literature, where truth must override intuitive belief to ensure integrity and safety.

[Arxiv](https://arxiv.org/abs/2506.06955)