# # 评测：从BERT到LLM，针对俄语文化新闻文本的命名实体识别模型

发布时间：2025年06月03日

`LLM应用` `文化遗产`

> Evaluating Named Entity Recognition Models for Russian Cultural News Texts: From BERT to LLM

# 摘要

> 本文针对俄罗斯新闻文本中涉及文化活动的人名识别（NER）挑战展开研究。研究采用了独特的SPbLitGuide数据集，该数据集涵盖了1999年至2019年间圣彼得堡的文化活动公告。本文对多种NER模型进行了全面评估，包括基于Transformer的成熟架构如DeepPavlov、RoBERTa和SpaCy，以及近期的大语言模型（LLMs）如GPT-3.5、GPT-4和GPT-4o。研究发现，GPT-4o在特定的JSON输出提示下表现最佳，F1得分为0.93。此外，GPT-4展现了最高的精确度，达到0.99。这项研究深化了我们对当前NER模型在处理如俄罗斯这类形态丰富的语言时的能力与局限性的理解，特别是在文化遗产领域，为研究者和实践者提供了宝贵的见解。后续使用GPT-4.1（2025年4月）进行的评估显示，无论是简单提示还是结构化提示，F1均达到了0.94，这表明模型家族的快速进展以及部署要求的简化。

> This paper addresses the challenge of Named Entity Recognition (NER) for person names within the specialized domain of Russian news texts concerning cultural events. The study utilizes the unique SPbLitGuide dataset, a collection of event announcements from Saint Petersburg spanning 1999 to 2019. A comparative evaluation of diverse NER models is presented, encompassing established transformer-based architectures such as DeepPavlov, RoBERTa, and SpaCy, alongside recent Large Language Models (LLMs) including GPT-3.5, GPT-4, and GPT-4o. Key findings highlight the superior performance of GPT-4o when provided with specific prompting for JSON output, achieving an F1 score of 0.93. Furthermore, GPT-4 demonstrated the highest precision at 0.99. The research contributes to a deeper understanding of current NER model capabilities and limitations when applied to morphologically rich languages like Russian within the cultural heritage domain, offering insights for researchers and practitioners. Follow-up evaluation with GPT-4.1 (April 2025) achieves F1=0.94 for both simple and structured prompts, demonstrating rapid progress across model families and simplified deployment requirements.

[Arxiv](https://arxiv.org/abs/2506.02589)