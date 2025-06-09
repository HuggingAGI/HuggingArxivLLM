# CONFER：一个用于评估自然语言推理模型在条件推理和预设方面表现的数据集。

发布时间：2025年06月06日

`LLM理论

理由：这篇论文探讨了自然语言推理模型在条件句预设推理任务中的表现，分析了现有模型的不足，并提出新数据集以评估其能力。研究重点在于模型的理论分析和性能评估，属于对大语言模型理论的深入探讨。` `人工智能`

> Let's CONFER: A Dataset for Evaluating Natural Language Inference Models on CONditional InFERence and Presupposition

# 摘要

> 自然语言推理（NLI）旨在判断两个句子之间是否存在蕴含、矛盾或中性关系。虽然NLI模型在多种推理任务中表现出色，但它们在处理细粒度语用推理，尤其是条件句中的预设推理方面的能力仍有待深入研究。为此，我们推出了CONFER这一全新数据集，专门用于评估NLI模型处理条件句推理的能力。我们对包括两个预训练模型在内的四种NLI模型进行了性能评估，以考察它们在条件推理上的泛化能力。此外，我们还测试了GPT-4o、LLaMA、Gemma和DeepSeek-R1等大型语言模型在零样本和少样本提示设置下的表现，以分析它们在有无上下文支持的情况下推断预设的能力。研究发现，NLI模型在条件句的预设推理上表现欠佳，且基于现有NLI数据集进行微调并不一定能显著提升其性能。

> Natural Language Inference (NLI) is the task of determining whether a sentence pair represents entailment, contradiction, or a neutral relationship. While NLI models perform well on many inference tasks, their ability to handle fine-grained pragmatic inferences, particularly presupposition in conditionals, remains underexplored. In this study, we introduce CONFER, a novel dataset designed to evaluate how NLI models process inference in conditional sentences. We assess the performance of four NLI models, including two pre-trained models, to examine their generalization to conditional reasoning. Additionally, we evaluate Large Language Models (LLMs), including GPT-4o, LLaMA, Gemma, and DeepSeek-R1, in zero-shot and few-shot prompting settings to analyze their ability to infer presuppositions with and without prior context. Our findings indicate that NLI models struggle with presuppositional reasoning in conditionals, and fine-tuning on existing NLI datasets does not necessarily improve their performance.

[Arxiv](https://arxiv.org/abs/2506.06133)