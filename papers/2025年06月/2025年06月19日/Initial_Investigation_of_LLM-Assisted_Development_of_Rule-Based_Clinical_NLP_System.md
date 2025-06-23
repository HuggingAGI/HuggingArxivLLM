# # 初步研究：LLM辅助开发基于规则的临床NLP系统

发布时间：2025年06月19日

`LLM应用

理由：这篇论文探讨了如何在基于规则的NLP系统开发中使用大型语言模型（LLMs），特别是在临床环境中。论文展示了LLMs在识别相关文本片段和提取关键词方面的有效性，从而为基于规则系统的开发提供了一种高效且透明的方法。这属于LLM的实际应用，因此归类为LLM应用。`

> Initial Investigation of LLM-Assisted Development of Rule-Based Clinical NLP System

# 摘要

> 尽管机器学习 (ML) 和大型语言模型 (LLMs) 取得了进展，但基于规则的自然语言处理 (NLP) 系统由于其可解释性和操作效率，在临床环境中仍然活跃。然而，它们的手动开发和维护非常耗时，特别是在语言变异性较大的任务中。为了解决这些限制，我们提出了一种新方法，仅在基于规则的系统开发阶段使用 LLMs。我们进行了初步实验，重点研究开发基于规则的 NLP 管道的前两个步骤：从临床记录中找到相关片段；从片段中提取用于基于规则的命名实体识别 (NER) 组件的有用关键词。我们的实验展示了在识别相关文本片段方面的出色召回率（Deepseek: 0.98，Qwen: 0.99），以及在提取 NER 关键术语方面的 1.0 分数。这项研究为 NLP 开发指明了一条有前途的新方向，与基于深度学习模型的解决方案相比，它能够实现半自动化或自动化的基于规则系统的开发，执行速度更快、成本效益更高且更加透明。

> Despite advances in machine learning (ML) and large language models (LLMs), rule-based natural language processing (NLP) systems remain active in clinical settings due to their interpretability and operational efficiency. However, their manual development and maintenance are labor-intensive, particularly in tasks with large linguistic variability. To overcome these limitations, we proposed a novel approach employing LLMs solely during the rule-based systems development phase. We conducted the initial experiments focusing on the first two steps of developing a rule-based NLP pipeline: find relevant snippets from the clinical note; extract informative keywords from the snippets for the rule-based named entity recognition (NER) component. Our experiments demonstrated exceptional recall in identifying clinically relevant text snippets (Deepseek: 0.98, Qwen: 0.99) and 1.0 in extracting key terms for NER. This study sheds light on a promising new direction for NLP development, enabling semi-automated or automated development of rule-based systems with significantly faster, more cost-effective, and transparent execution compared with deep learning model-based solutions.

[Arxiv](https://arxiv.org/abs/2506.16628)