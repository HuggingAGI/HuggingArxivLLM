# 文本到CadQuery：一种基于可扩展大模型能力的全新CAD生成范式

发布时间：2025年05月10日

`LLM应用` `软件开发`

> Text-to-CadQuery: A New Paradigm for CAD Generation with Scalable Large Model Capabilities

# 摘要

> 计算机辅助设计（CAD）是现代工程和制造的基石，但创建CAD模型仍需专业知识与专业软件。大型语言模型（LLMs）的最新进展为生成式CAD带来了新可能，让自然语言直接转化为参数化3D模型成为可能。然而，现有方法生成的任务特定命令序列无法被预训练模型直接处理，必须先转换为CAD表示（如CAD向量），这不仅增加了复杂性，还需从头训练模型。为解决这一问题，我们提出直接从文本生成CadQuery代码，利用预训练LLMs的优势，无需中间表示即可生成3D模型。由于LLMs在Python生成和空间推理方面已表现出色，因此在Text-to-CadQuery数据上对其进行微调效果显著。鉴于模型能力通常随规模提升而增强，我们推测更大模型在微调后表现更佳。为此，我们扩展了Text2CAD数据集，增加了17万条CadQuery注释。我们对六种不同规模的开源LLMs进行了微调，观察到一致的性能提升。我们的最佳模型在top-1精确匹配上达到69.3%，较之前提升了10.5个百分点，并将Chamfer Distance减少了48.6%。项目页面：https://github.com/Text-to-CadQuery/Text-to-CadQuery。

> Computer-aided design (CAD) is fundamental to modern engineering and manufacturing, but creating CAD models still requires expert knowledge and specialized software. Recent advances in large language models (LLMs) open up the possibility of generative CAD, where natural language is directly translated into parametric 3D models. However, most existing methods generate task-specific command sequences that pretrained models cannot directly handle. These sequences must be converted into CAD representations such as CAD vectors before a 3D model can be produced, which requires training models from scratch and adds unnecessary complexity. To tackle this issue, we propose generating CadQuery code directly from text, leveraging the strengths of pretrained LLMs to produce 3D models without intermediate representations, using this Python-based scripting language. Since LLMs already excel at Python generation and spatial reasoning, fine-tuning them on Text-to-CadQuery data proves highly effective. Given that these capabilities typically improve with scale, we hypothesize that larger models will perform better after fine-tuning. To enable this, we augment the Text2CAD dataset with 170,000 CadQuery annotations. We fine-tune six open-source LLMs of varying sizes and observe consistent improvements. Our best model achieves a top-1 exact match of 69.3%, up from 58.8%, and reduces Chamfer Distance by 48.6%. Project page: https://github.com/Text-to-CadQuery/Text-to-CadQuery.

[Arxiv](https://arxiv.org/abs/2505.06507)