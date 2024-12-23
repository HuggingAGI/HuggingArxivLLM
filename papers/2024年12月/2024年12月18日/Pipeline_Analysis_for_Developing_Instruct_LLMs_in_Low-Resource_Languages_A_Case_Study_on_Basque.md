# 针对在低资源语言中开发指导型大语言模型的流水线分析：以巴斯克语为例

发布时间：2024年12月18日

`LLM应用` `低资源语言`

> Pipeline Analysis for Developing Instruct LLMs in Low-Resource Languages: A Case Study on Basque

# 摘要

> 大型语言模型（LLMs）往往针对像英语这类资源丰富的语言进行优化，这加大了高资源语言与资源匮乏语言之间的差距。此项工作围绕预训练、指令调优以及与人类偏好对齐这三个关键阶段，对开发能以低资源语言（特别是巴斯克语）遵循指令的模型策略展开了详尽分析。我们的发现表明，利用约 6 亿词的高质量巴斯克语语料库进行持续预训练，能让基础模型的自然语言理解（NLU）能力提升 12 个点以上。而且，使用自动翻译的数据集进行指令调优和人类偏好对齐效果显著，使指令遵循性能提升 24 个点。最终的模型 Llama-eus-8B 和 Llama-eus-8B-instruct，在 10B 以下参数类别中为巴斯克语树立了新的标杆。

> Large language models (LLMs) are typically optimized for resource-rich languages like English, exacerbating the gap between high-resource and underrepresented languages. This work presents a detailed analysis of strategies for developing a model capable of following instructions in a low-resource language, specifically Basque, by focusing on three key stages: pre-training, instruction tuning, and alignment with human preferences. Our findings demonstrate that continual pre-training with a high-quality Basque corpus of around 600 million words improves natural language understanding (NLU) of the foundational model by over 12 points. Moreover, instruction tuning and human preference alignment using automatically translated datasets proved highly effective, resulting in a 24-point improvement in instruction-following performance. The resulting models, Llama-eus-8B and Llama-eus-8B-instruct, establish a new state-of-the-art for Basque in the sub-10B parameter category.

[Arxiv](https://arxiv.org/abs/2412.13922)