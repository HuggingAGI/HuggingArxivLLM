# ArtSeek：基于多模态上下文推理与后阶段交互检索实现艺术品深度理解

发布时间：2025年07月29日

`RAG` `多模态AI`

> ArtSeek: Deep artwork understanding via multimodal in-context reasoning and late interaction retrieval

# 摘要

> 分析数字化艺术品不仅需要视觉解读，还需要深入理解丰富的艺术、背景和历史知识。我们推出ArtSeek——一个结合多模态大语言模型与检索增强生成的全新艺术分析框架。与现有方法不同，ArtSeek仅依赖于图像输入，使其适用于大多数数字化收藏中常见的无Wikidata/Wikipedia链接的艺术品。

ArtSeek的核心由三大模块组成：基于晚期交互检索的智能多模态检索模块、用于预测艺术家、流派、风格、媒介和标签的对比多任务分类网络，以及通过Qwen2.5-VL中的in-context示例实现的复杂视觉问答和艺术品解释的智能推理策略。这一方法的关键在于WikiFragments——一个维基百科规模的图像-文本片段数据集，专为支持基于知识的多模态推理而整理。

在多个基准测试中，我们的框架取得了最新成果：风格分类上的F1值比GraphCLIP提升了8.4%，在ArtPedia上的captioning任务中获得了7.1的BLEU@1提升。定性分析显示，ArtSeek不仅能解释视觉主题、推断历史背景，还能检索相关知识，即使是较不为人知的作品也能应对自如。

尽管专注于视觉艺术，但我们的方法可推广到其他需要外部知识的领域，支持可扩展的多模态AI研究。数据集和源代码将在https://github.com/cilabuniba/artseek公开发布。

> Analyzing digitized artworks presents unique challenges, requiring not only visual interpretation but also a deep understanding of rich artistic, contextual, and historical knowledge. We introduce ArtSeek, a multimodal framework for art analysis that combines multimodal large language models with retrieval-augmented generation. Unlike prior work, our pipeline relies only on image input, enabling applicability to artworks without links to Wikidata or Wikipedia-common in most digitized collections. ArtSeek integrates three key components: an intelligent multimodal retrieval module based on late interaction retrieval, a contrastive multitask classification network for predicting artist, genre, style, media, and tags, and an agentic reasoning strategy enabled through in-context examples for complex visual question answering and artwork explanation via Qwen2.5-VL. Central to this approach is WikiFragments, a Wikipedia-scale dataset of image-text fragments curated to support knowledge-grounded multimodal reasoning. Our framework achieves state-of-the-art results on multiple benchmarks, including a +8.4% F1 improvement in style classification over GraphCLIP and a +7.1 BLEU@1 gain in captioning on ArtPedia. Qualitative analyses show that ArtSeek can interpret visual motifs, infer historical context, and retrieve relevant knowledge, even for obscure works. Though focused on visual arts, our approach generalizes to other domains requiring external knowledge, supporting scalable multimodal AI research. Both the dataset and the source code will be made publicly available at https://github.com/cilabuniba/artseek.

[Arxiv](https://arxiv.org/abs/2507.21917)