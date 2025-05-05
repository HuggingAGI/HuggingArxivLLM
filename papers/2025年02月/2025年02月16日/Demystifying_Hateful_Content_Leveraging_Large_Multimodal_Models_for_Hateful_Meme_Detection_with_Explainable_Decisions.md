# 解构恶意内容：借助大型多模态模型实现恶意表情包检测与可解释决策

发布时间：2025年02月16日

`LLM应用

理由：该论文探讨了如何利用大型多模态模型（LMMs）来解决仇恨表情符号检测的问题，属于将LLM应用于实际任务的范畴。` `社交媒体` `人工智能`

> Demystifying Hateful Content: Leveraging Large Multimodal Models for Hateful Meme Detection with Explainable Decisions

# 摘要

> 仇恨表情符号检测作为一项多模态任务，面临解析隐含仇恨信息及上下文线索的双重挑战。此前的研究主要通过微调预训练的视觉语言模型（PT-VLMs）来解决这一问题，这些模型利用预训练知识和注意力机制来理解表情符号内容。然而，由于对隐含知识和复杂注意力机制的依赖，这些模型的决策过程难以解释，这对于建立用户信任至关重要。本文提出了一种名为IntMeme的新框架，利用大型多模态模型（LMMs）进行仇恨表情符号分类，同时确保决策的可解释性。IntMeme在提升表情符号审核的准确性和可解释性方面表现出色。该框架通过LMMs生成人类可理解的、富有洞见的表情符号分析，深入挖掘多模态内容及其上下文。此外，IntMeme为表情符号及其解读配备了独立的编码模块，并通过融合两者信息来提升分类性能。我们的方法有效解决了PT-VLMs在不透明性和误分类方面的固有问题，同时优化了LMMs在仇恨表情符号检测中的应用。通过在三个不同数据集上进行的全面实验，我们验证了IntMeme的优越性，其表现显著优于现有的最先进模型。

> Hateful meme detection presents a significant challenge as a multimodal task due to the complexity of interpreting implicit hate messages and contextual cues within memes. Previous approaches have fine-tuned pre-trained vision-language models (PT-VLMs), leveraging the knowledge they gained during pre-training and their attention mechanisms to understand meme content. However, the reliance of these models on implicit knowledge and complex attention mechanisms renders their decisions difficult to explain, which is crucial for building trust in meme classification. In this paper, we introduce IntMeme, a novel framework that leverages Large Multimodal Models (LMMs) for hateful meme classification with explainable decisions. IntMeme addresses the dual challenges of improving both accuracy and explainability in meme moderation. The framework uses LMMs to generate human-like, interpretive analyses of memes, providing deeper insights into multimodal content and context. Additionally, it uses independent encoding modules for both memes and their interpretations, which are then combined to enhance classification performance. Our approach addresses the opacity and misclassification issues associated with PT-VLMs, optimizing the use of LMMs for hateful meme detection. We demonstrate the effectiveness of IntMeme through comprehensive experiments across three datasets, showcasing its superiority over state-of-the-art models.

[Arxiv](https://arxiv.org/abs/2502.11073)