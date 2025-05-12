# # ArtRAG：结合结构化上下文的检索增强生成，助力视觉艺术理解

发布时间：2025年05月09日

`RAG` `视觉艺术`

> ArtRAG: Retrieval-Augmented Generation with Structured Context for Visual Art Understanding

# 摘要

> 理解视觉艺术不仅需要识别物体，还需要从文化、历史和风格等多个角度进行推理。虽然多模态大语言模型（MLLMs）在普通图像描述上表现优异，但它们往往难以捕捉到艺术品所需要的细腻解读。为此，我们提出了 ArtRAG——一个无需训练的创新框架，通过结合结构化知识与增强检索生成（RAG），实现多角度的艺术品阐释。ArtRAG 自动构建艺术背景知识图谱（ACKG），将艺术家、流派、主题和历史事件等元素组织成一个丰富且易理解的图谱。推理时，多粒度结构化检索器会筛选出语义和拓扑上相关的子图，为生成提供指导。这使 MLLMs 能够输出具有深厚文化背景和上下文依据的艺术描述。实验结果显示，ArtRAG 在 SemArt 和 Artpedia 数据集上的表现超越了多个强基线模型。人类评估进一步证实，ArtRAG 生成的解释不仅连贯且富有见地，更蕴含丰富的文化内涵。

> Understanding visual art requires reasoning across multiple perspectives -- cultural, historical, and stylistic -- beyond mere object recognition. While recent multimodal large language models (MLLMs) perform well on general image captioning, they often fail to capture the nuanced interpretations that fine art demands. We propose ArtRAG, a novel, training-free framework that combines structured knowledge with retrieval-augmented generation (RAG) for multi-perspective artwork explanation. ArtRAG automatically constructs an Art Context Knowledge Graph (ACKG) from domain-specific textual sources, organizing entities such as artists, movements, themes, and historical events into a rich, interpretable graph. At inference time, a multi-granular structured retriever selects semantically and topologically relevant subgraphs to guide generation. This enables MLLMs to produce contextually grounded, culturally informed art descriptions. Experiments on the SemArt and Artpedia datasets show that ArtRAG outperforms several heavily trained baselines. Human evaluations further confirm that ArtRAG generates coherent, insightful, and culturally enriched interpretations.

[Arxiv](https://arxiv.org/abs/2505.06020)