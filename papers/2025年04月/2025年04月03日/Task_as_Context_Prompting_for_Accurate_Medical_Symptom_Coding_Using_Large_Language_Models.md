# 利用大型语言模型，通过任务作为上下文提示实现准确的医学症状编码

发布时间：2025年04月03日

`LLM应用` `药物警戒`

> Task as Context Prompting for Accurate Medical Symptom Coding Using Large Language Models

# 摘要

> 从非结构化临床文本（如疫苗安全性报告）中准确提取和编码医学症状，是药物警戒和安全监测中的关键任务。本研究中的症状编码专注于识别并细致地将症状提及与标准化词汇表（如MedDRA）关联起来，这与更广泛的医学编码任务不同。传统方法通常将症状提取和链接视为独立的工作流程，这使得它们在处理临床叙述中的变化和复杂性时效果有限，尤其是在面对罕见案例时。大型语言模型（LLMs）的最新进展为这一领域带来了新的可能性，但实现稳定可靠的性能仍具挑战性。为了解决这些问题，我们提出了Task as Context (TACO) Prompting，这是一种通过将任务特定的上下文嵌入到LLM提示中，从而将提取和链接任务统一起来的创新框架。我们还开发了SYMPCODER，一个基于疫苗不良事件报告系统（VAERS）报告的人工标注数据集，并设计了一个两阶段评估框架，以全面评估症状链接的准确性和提及的保真度。通过对多个LLMs（包括Llama2-chat、Jackalope-7b、GPT-3.5 Turbo、GPT-4 Turbo和GPT-4o）的全面评估，我们证明了TACO在提升定制任务（如症状编码）的灵活性和准确性方面的显著优势，这为更具体的编码任务和临床文本处理方法的发展奠定了基础。

> Accurate medical symptom coding from unstructured clinical text, such as vaccine safety reports, is a critical task with applications in pharmacovigilance and safety monitoring. Symptom coding, as tailored in this study, involves identifying and linking nuanced symptom mentions to standardized vocabularies like MedDRA, differentiating it from broader medical coding tasks. Traditional approaches to this task, which treat symptom extraction and linking as independent workflows, often fail to handle the variability and complexity of clinical narratives, especially for rare cases. Recent advancements in Large Language Models (LLMs) offer new opportunities but face challenges in achieving consistent performance. To address these issues, we propose Task as Context (TACO) Prompting, a novel framework that unifies extraction and linking tasks by embedding task-specific context into LLM prompts. Our study also introduces SYMPCODER, a human-annotated dataset derived from Vaccine Adverse Event Reporting System (VAERS) reports, and a two-stage evaluation framework to comprehensively assess both symptom linking and mention fidelity. Our comprehensive evaluation of multiple LLMs, including Llama2-chat, Jackalope-7b, GPT-3.5 Turbo, GPT-4 Turbo, and GPT-4o, demonstrates TACO's effectiveness in improving flexibility and accuracy for tailored tasks like symptom coding, paving the way for more specific coding tasks and advancing clinical text processing methodologies.

[Arxiv](https://arxiv.org/abs/2504.03051)