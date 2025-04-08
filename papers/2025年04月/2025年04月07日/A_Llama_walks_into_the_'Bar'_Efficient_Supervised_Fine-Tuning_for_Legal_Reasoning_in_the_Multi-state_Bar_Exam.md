# 一只羊驼走进了'酒吧'：多州律师资格考试中的高效监督微调与法律推理优化

发布时间：2025年04月07日

`LLM应用

理由：这篇论文探讨了如何在法律推理任务中应用和优化大型语言模型，特别是在法律问答中的微调和结构化推理方法。研究集中在模型的应用和实际效果上，属于LLM应用领域。` `问答系统`

> A Llama walks into the 'Bar': Efficient Supervised Fine-Tuning for Legal Reasoning in the Multi-state Bar Exam

# 摘要

> 法律推理任务对大型语言模型（LLMs）提出了独特挑战，原因在于该领域专业知识的复杂性和推理过程的独特性。本文研究了较小规模的语言模型（如Llama 2 7B和Llama 3 8B）如何在有限的1,514个多州律师资格考试（MBE）问题数据集上进行微调，以提升法律问答的准确性。我们使用JD Advising授权的2022年MBE问题进行评估，这些数据与'GPT-4通过律师资格考试'研究中使用的相同。我们的方法涉及从7个法律领域中各收集约200个问题。我们利用Llama 3（70B）对数据集进行蒸馏，将解释转化为结构化的IRAC（问题、规则、应用、结论）格式，作为一种引导推理过程，以检验其是否能比未蒸馏的数据集带来更好的性能。我们将未经微调的模型与经过不同领域样本量训练的监督微调（SFT）模型进行对比，研究其对准确性和提示遵循性的影响。此外，我们还分析了SFT后的选项选择偏差及其缓解方法。同时，我们在多个变量上整合了性能表现：提示类型（few-shot与zero-shot）、答案顺序（选项优先与解释优先）、响应格式（编号列表、Markdown、JSON）以及不同的解码温度。我们的研究发现，领域特定的SFT有助于某些模型配置接近人类基线性能，尽管计算资源有限且数据集相对较小。我们发布了收集的SFT数据集以及针对MBE性能优化的监督微调（SFT）适配器系列。这为在较小规模的LLMs中实现有效的法律问答设定了实际的资源下限。

> Legal reasoning tasks present unique challenges for large language models (LLMs) due to the complexity of domain-specific knowledge and reasoning processes. This paper investigates how effectively smaller language models (Llama 2 7B and Llama 3 8B) can be fine-tuned with a limited dataset of 1,514 Multi-state Bar Examination (MBE) questions to improve legal question answering accuracy. We evaluate these models on the 2022 MBE questions licensed from JD Advising, the same dataset used in the 'GPT-4 passes the Bar exam' study. Our methodology involves collecting approximately 200 questions per legal domain across 7 domains. We distill the dataset using Llama 3 (70B) to transform explanations into a structured IRAC (Issue, Rule, Application, Conclusion) format as a guided reasoning process to see if it results in better performance over the non-distilled dataset. We compare the non-fine-tuned models against their supervised fine-tuned (SFT) counterparts, trained for different sample sizes per domain, to study the effect on accuracy and prompt adherence. We also analyse option selection biases and their mitigation following SFT. In addition, we consolidate the performance across multiple variables: prompt type (few-shot vs zero-shot), answer ordering (chosen-option first vs generated-explanation first), response format (Numbered list vs Markdown vs JSON), and different decoding temperatures. Our findings show that domain-specific SFT helps some model configurations achieve close to human baseline performance, despite limited computational resources and a relatively small dataset. We release both the gathered SFT dataset and the family of Supervised Fine-tuned (SFT) adapters optimised for MBE performance. This establishes a practical lower bound on resources needed towards achieving effective legal question answering in smaller LLMs.

[Arxiv](https://arxiv.org/abs/2504.04945)