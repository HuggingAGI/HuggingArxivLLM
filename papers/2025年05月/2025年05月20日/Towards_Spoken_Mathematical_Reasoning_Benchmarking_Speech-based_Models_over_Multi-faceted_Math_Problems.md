# 迈向口语化数学推理：基于语音模型在多维度数学问题上的基准测试

发布时间：2025年05月20日

`LLM应用

摘要中讨论了大型语言模型（LLMs）和多模态大型语言模型（MLLMs）在数学推理任务中的应用，特别是从语音输入中进行数学推理的能力。研究者提出了一个新的基准测试Spoken-MQA，用于评估语音模型在数学推理任务中的表现，并分析了当前模型的优缺点。这属于对大型语言模型在特定任务中的应用研究，因此归类为LLM应用。` `数学推理` `语音处理`

> Towards Spoken Mathematical Reasoning: Benchmarking Speech-based Models over Multi-faceted Math Problems

# 摘要

> 近期，大型语言模型（LLMs）和多模态大型语言模型（MLLMs）在广泛任务中展现出强大的推理能力。然而，它们从语音输入中进行数学推理的能力仍有待深入探索。此前关于语音模态的研究大多聚焦于事实性语音理解和简单音频推理，对逻辑逐步推理的探讨较少，尤其是数学问题求解所需的推理能力。为填补这一研究空白，我们推出 Spoken Math Question Answering（Spoken-MQA），这是一个全新基准测试，旨在评估基于语音的模型（包括级联模型（ASR + LLMs）和端到端语音 LLMs）的数学推理能力。Spoken-MQA 涵盖了多样化的数学问题，包括纯算术、单步与多步情境推理以及知识导向推理问题，所有问题均以清晰自然的口语形式呈现。通过大量实验，我们发现：(1) 部分语音 LLMs 在涉及基础算术的情境推理任务中表现优异，但面对直接算术问题仍显不足；(2) 当前 LLMs 对 LaTex 编写的符号数学表达式有明显偏好，难以准确解析口语化数学表达；(3) 当前语音 LLMs 的数学知识推理能力明显减弱。

> Recent advances in large language models (LLMs) and multimodal LLMs (MLLMs) have led to strong reasoning ability across a wide range of tasks. However, their ability to perform mathematical reasoning from spoken input remains underexplored. Prior studies on speech modality have mostly focused on factual speech understanding or simple audio reasoning tasks, providing limited insight into logical step-by-step reasoning, such as that required for mathematical problem solving. To address this gap, we introduce Spoken Math Question Answering (Spoken-MQA), a new benchmark designed to evaluate the mathematical reasoning capabilities of speech-based models, including both cascade models (ASR + LLMs) and end-to-end speech LLMs. Spoken-MQA covers a diverse set of math problems, including pure arithmetic, single-step and multi-step contextual reasoning, and knowledge-oriented reasoning problems, all presented in unambiguous natural spoken language. Through extensive experiments, we find that: (1) while some speech LLMs perform competitively on contextual reasoning tasks involving basic arithmetic, they still struggle with direct arithmetic problems; (2) current LLMs exhibit a strong bias toward symbolic mathematical expressions written in LaTex and have difficulty interpreting verbalized mathematical expressions; and (3) mathematical knowledge reasoning abilities are significantly degraded in current speech LLMs.

[Arxiv](https://arxiv.org/abs/2505.15000)