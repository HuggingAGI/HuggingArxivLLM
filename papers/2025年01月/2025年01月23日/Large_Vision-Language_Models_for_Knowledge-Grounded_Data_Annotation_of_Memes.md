# 大型视觉-语言模型助力迷因数据的知识驱动标注

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型视觉-语言模型（如CLIP）来生成高质量的图像描述和表情包描述，并提出了一个基于跨模态嵌入的表情包-文本检索模型（mtrCLIP）。这些工作都是基于大型语言模型（LLM）的应用，特别是在多模态（视觉和文本）任务中的应用。因此，这篇论文应归类为LLM应用。` `社交媒体`

> Large Vision-Language Models for Knowledge-Grounded Data Annotation of Memes

# 摘要

> # 摘要
表情包作为一种融合视觉与文本的沟通方式，已成为传递幽默、讽刺和文化信息的有力工具。现有研究多聚焦于情感分类、表情包生成、传播、解释、比喻语言及社会语言学等领域，但对表情包的深层理解及表情包-文本检索的关注较少。为此，我们推出了ClassicMemes-50-templates (CM50)，一个包含33,000多个表情包的大规模数据集，围绕50个流行模板构建。我们还开发了一套自动化知识驱动的注释流程，借助大型视觉-语言模型生成高质量的图像描述、表情包描述及文学手法标签，有效解决了手动注释的高成本问题。此外，我们提出了基于跨模态嵌入的表情包-文本检索CLIP模型（mtrCLIP），显著提升了检索性能。本研究的贡献包括：（1）一个面向大规模表情包研究的新数据集，（2）一个可扩展的表情包注释框架，以及（3）一个专为表情包-文本检索优化的微调CLIP模型，旨在推动表情包的大规模理解与分析。

> Memes have emerged as a powerful form of communication, integrating visual and textual elements to convey humor, satire, and cultural messages. Existing research has focused primarily on aspects such as emotion classification, meme generation, propagation, interpretation, figurative language, and sociolinguistics, but has often overlooked deeper meme comprehension and meme-text retrieval. To address these gaps, this study introduces ClassicMemes-50-templates (CM50), a large-scale dataset consisting of over 33,000 memes, centered around 50 popular meme templates. We also present an automated knowledge-grounded annotation pipeline leveraging large vision-language models to produce high-quality image captions, meme captions, and literary device labels overcoming the labor intensive demands of manual annotation. Additionally, we propose a meme-text retrieval CLIP model (mtrCLIP) that utilizes cross-modal embedding to enhance meme analysis, significantly improving retrieval performance. Our contributions include:(1) a novel dataset for large-scale meme study, (2) a scalable meme annotation framework, and (3) a fine-tuned CLIP for meme-text retrieval, all aimed at advancing the understanding and analysis of memes at scale.

[Arxiv](https://arxiv.org/abs/2501.13851)