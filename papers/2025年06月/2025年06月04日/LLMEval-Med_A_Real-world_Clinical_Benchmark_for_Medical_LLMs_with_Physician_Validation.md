# LLMEval-Med：面向医疗LLMs的真实临床基准测试，并经过医生验证。

发布时间：2025年06月04日

`LLM应用

摘要中的论文专注于评估大型语言模型在医学领域的应用，探讨了现有评测基准的局限性，并提出了一种新的基准LLMEval-Med，用于更全面和真实地评估模型在医学场景中的表现。这属于LLM的应用层面，因此分类为LLM应用。`

> LLMEval-Med: A Real-world Clinical Benchmark for Medical LLMs with Physician Validation

# 摘要

> 医学领域大型语言模型评估至关重要，因其应用容不得半点差错。现有医学评测基准主要分为医学考试、综合医学及专业评估三类，但存在试题设计单一（多为选择题）、数据来源不真实（少有临床实情）及评估方式欠佳（复杂推理能力考量不足）等局限。为此，我们推出 LLMEval-Med，一个涵盖五个核心医学领域的全新基准，包含基于真实电子健康记录和专家设计临床场景的 2,996 个问题。我们还开发了自动化评估流程，将专家设计的评估清单融入 LLM 评测框架。此外，通过人机一致性分析验证机器评分，并依据专家反馈持续优化评估清单和提示，确保评估的可靠性。我们在 LLMEval-Med 上评估了 13 个 LLM（包括专业医学、开源及闭源模型），为 LLM 在医学领域的安全有效应用提供了重要参考。数据集已开放于 https://github.com/llmeval/LLMEval-Med。


> Evaluating large language models (LLMs) in medicine is crucial because medical applications require high accuracy with little room for error. Current medical benchmarks have three main types: medical exam-based, comprehensive medical, and specialized assessments. However, these benchmarks have limitations in question design (mostly multiple-choice), data sources (often not derived from real clinical scenarios), and evaluation methods (poor assessment of complex reasoning). To address these issues, we present LLMEval-Med, a new benchmark covering five core medical areas, including 2,996 questions created from real-world electronic health records and expert-designed clinical scenarios. We also design an automated evaluation pipeline, incorporating expert-developed checklists into our LLM-as-Judge framework. Furthermore, our methodology validates machine scoring through human-machine agreement analysis, dynamically refining checklists and prompts based on expert feedback to ensure reliability. We evaluate 13 LLMs across three categories (specialized medical models, open-source models, and closed-source models) on LLMEval-Med, providing valuable insights for the safe and effective deployment of LLMs in medical domains. The dataset is released in https://github.com/llmeval/LLMEval-Med.

[Arxiv](https://arxiv.org/abs/2506.04078)