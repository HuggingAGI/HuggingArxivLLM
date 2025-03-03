# UoR-NCL 参加 SemEval-2025 任务 1：基于生成式大语言模型与 CLIP 模型，构建跨语言多模态习语表达的表示方法

发布时间：2025年02月28日

`LLM应用` `图像处理`

> UoR-NCL at SemEval-2025 Task 1: Using Generative LLMs and CLIP Models for Multilingual Multimodal Idiomaticity Representation

# 摘要

> SemEval-2025 任务1聚焦于根据可能携带习语意义的名义复合词对图像进行排名，这些意义可能存在于英语和巴西葡萄牙语中。为应对这一挑战，本研究创新性地结合生成型大型语言模型（LLMs）和多语言CLIP模型，提升习语复合词的表征能力。LLMs生成潜在习语复合词的习语意义，丰富其语义解释。这些意义随后通过多语言CLIP模型进行编码，作为图像排名的表征。研究中应用了对比学习和数据增强技术来微调这些嵌入，以提升性能。实验结果表明，通过本方法提取的多模态表征优于仅基于原始名义复合词的表征。微调方法展现了良好前景，但其效果不如未进行微调的嵌入。本文所用的源代码可在https://github.com/tongwu17/SemEval-2025-Task1-UoR-NCL获取。

> SemEval-2025 Task 1 focuses on ranking images based on their alignment with a given nominal compound that may carry idiomatic meaning in both English and Brazilian Portuguese. To address this challenge, this work uses generative large language models (LLMs) and multilingual CLIP models to enhance idiomatic compound representations. LLMs generate idiomatic meanings for potentially idiomatic compounds, enriching their semantic interpretation. These meanings are then encoded using multilingual CLIP models, serving as representations for image ranking. Contrastive learning and data augmentation techniques are applied to fine-tune these embeddings for improved performance. Experimental results show that multimodal representations extracted through this method outperformed those based solely on the original nominal compounds. The fine-tuning approach shows promising outcomes but is less effective than using embeddings without fine-tuning. The source code used in this paper is available at https://github.com/tongwu17/SemEval-2025-Task1-UoR-NCL.

[Arxiv](https://arxiv.org/abs/2502.20984)