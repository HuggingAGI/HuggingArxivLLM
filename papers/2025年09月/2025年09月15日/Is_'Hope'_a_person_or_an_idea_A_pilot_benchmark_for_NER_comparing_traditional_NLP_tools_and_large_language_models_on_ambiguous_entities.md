# “Hope”究竟是人还是概念？命名实体识别（NER）初步基准研究：在模糊实体识别上对比传统NLP工具与大型语言模型

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Is 'Hope' a person or an idea? A pilot benchmark for NER: comparing traditional NLP tools and large language models on ambiguous entities

# 摘要

> 本试点研究构建了一个小规模但标注精细的命名实体识别（NER）性能基准，涉及六个系统：三个非LLM自然语言处理工具（NLTK、spaCy、Stanza）和三个通用大型语言模型（LLMs：Gemini-1.5-flash、DeepSeek-V3、Qwen-3-4B）。该数据集包含119个标记，涉及五种实体类型（PERSON、LOCATION、ORGANIZATION、DATE、TIME）。我们以人工标注的黄金标准数据集为参照，采用F1分数对各系统输出进行了评估。结果显示，在识别人名等上下文敏感实体时，LLM总体优于传统工具，其中Gemini的平均F1分数最高。不过，Stanza等传统系统在LOCATION和DATE等结构化标签的识别上一致性更高。此外，我们发现LLM之间存在性能差异，尤其是在处理时间表达式和多词组织实体时。研究结果表明，尽管LLM在上下文理解方面更具优势，但传统工具在特定任务中仍保有竞争力，这为模型选择提供了参考依据。

> This pilot study presents a small-scale but carefully annotated benchmark of Named Entity Recognition (NER) performance across six systems: three non-LLM NLP tools (NLTK, spaCy, Stanza) and three general-purpose large language models (LLMs: Gemini-1.5-flash, DeepSeek-V3, Qwen-3-4B). The dataset contains 119 tokens covering five entity types (PERSON, LOCATION, ORGANIZATION, DATE, TIME). We evaluated each system's output against the manually annotated gold standard dataset using F1-score. The results show that LLMs generally outperform conventional tools in recognizing context-sensitive entities like person names, with Gemini achieving the highest average F1-score. However, traditional systems like Stanza demonstrate greater consistency in structured tags such as LOCATION and DATE. We also observed variability among LLMs, particularly in handling temporal expressions and multi-word organizations. Our findings highlight that while LLMs offer improved contextual understanding, traditional tools remain competitive in specific tasks, informing model selection.

[Arxiv](https://arxiv.org/abs/2509.12098)