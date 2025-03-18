# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月15日

`RAG` `罕见病诊断`

> Integrating Chain-of-Thought and Retrieval Augmented Generation Enhances Rare Disease Diagnosis from Clinical Notes

# 摘要

> # 背景
数项研究表明，大型语言模型（LLMs）在罕见病的表型驱动基因优先级排序方面表现不佳。这些研究通常使用人类表型本体论（HPO）术语来提示GPT和LLaMA等基础模型，以预测候选基因。然而，在现实环境中，基础模型并未针对临床诊断等特定领域任务进行优化，且输入通常是未结构化的临床笔记，而非标准化术语。如何指导LLMs从非结构化临床笔记中预测候选基因或疾病诊断仍是一个主要挑战。

# 方法
我们引入了基于RAG的CoT和基于CoT的RAG两种方法，结合了链式思维（CoT）和增强检索生成（RAG）来分析临床笔记。一个包含五个问题的CoT协议模拟了专家推理，而RAG则从HPO和OMIM（人类孟德尔遗传在线）等来源中检索数据。我们在罕见病数据集上评估了这些方法，包括：
- 5,980份基于Phenopacket的笔记
- 255份基于文献的叙述
- 220份费城儿童医院的内部临床笔记

# 结果
我们发现：
- 近期的基础模型，包括Llama 3.3-70B-Instruct和DeepSeek-R1-Distill-Llama-70B，在候选基因优先级排序方面优于早期版本如Llama 2和GPT-3.5
- 基于RAG的CoT和基于CoT的RAG在从临床笔记中进行候选基因优先级排序方面均优于基础模型
- 特别是，两种方法在基于Phenopacket的临床笔记上，使用DeepSeek作为骨干模型时，前10位基因的准确率均超过40%

此外，基于RAG的CoT在处理高质量笔记时表现更佳，因为早期检索可以将后续推理步骤锚定在领域特定的证据上；而基于CoT的RAG在处理冗长且噪声较大的笔记时具有优势。


> Background: Several studies show that large language models (LLMs) struggle with phenotype-driven gene prioritization for rare diseases. These studies typically use Human Phenotype Ontology (HPO) terms to prompt foundation models like GPT and LLaMA to predict candidate genes. However, in real-world settings, foundation models are not optimized for domain-specific tasks like clinical diagnosis, yet inputs are unstructured clinical notes rather than standardized terms. How LLMs can be instructed to predict candidate genes or disease diagnosis from unstructured clinical notes remains a major challenge. Methods: We introduce RAG-driven CoT and CoT-driven RAG, two methods that combine Chain-of-Thought (CoT) and Retrieval Augmented Generation (RAG) to analyze clinical notes. A five-question CoT protocol mimics expert reasoning, while RAG retrieves data from sources like HPO and OMIM (Online Mendelian Inheritance in Man). We evaluated these approaches on rare disease datasets, including 5,980 Phenopacket-derived notes, 255 literature-based narratives, and 220 in-house clinical notes from Childrens Hospital of Philadelphia. Results: We found that recent foundations models, including Llama 3.3-70B-Instruct and DeepSeek-R1-Distill-Llama-70B, outperformed earlier versions such as Llama 2 and GPT-3.5. We also showed that RAG-driven CoT and CoT-driven RAG both outperform foundation models in candidate gene prioritization from clinical notes; in particular, both methods with DeepSeek backbone resulted in a top-10 gene accuracy of over 40% on Phenopacket-derived clinical notes. RAG-driven CoT works better for high-quality notes, where early retrieval can anchor the subsequent reasoning steps in domain-specific evidence, while CoT-driven RAG has advantage when processing lengthy and noisy notes.

[Arxiv](https://arxiv.org/abs/2503.12286)