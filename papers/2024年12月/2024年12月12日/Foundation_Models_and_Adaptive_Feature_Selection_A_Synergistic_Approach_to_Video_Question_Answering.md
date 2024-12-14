# 基础模型与自适应特征选择：视频问答的协同之道

发布时间：2024年12月12日

`LLM应用` `问答系统`

> Foundation Models and Adaptive Feature Selection: A Synergistic Approach to Video Question Answering

# 摘要

> 这篇论文应对了视频问答（VideoQA）这一棘手挑战。尽管已有显著进展，但当下的方法难以将问题与视频帧及语义对象级抽象有效融合，从而创建具有问题感知的视频表示。我们推出了局部-全局问题感知视频嵌入（LGQAVE），其涵盖三项主要创新，能更好地整合多模态知识，并突出与特定问题相关的语义视觉概念。LGQAVE 摒弃了传统的临时帧采样方式，借助交叉注意力机制精准识别与问题最相关的帧。它运用不同的图捕捉这些帧内对象的动态，并通过 miniGPT 模型将其与问题语义相结合。这些图由问题感知动态图转换器（Q-DGT）处理，该转换器优化输出，以形成细致的全局和局部视频表示。另外，一个交叉注意力模块整合了这些局部和全局嵌入，生成最终的视频嵌入，语言模型借此生成答案。在多个基准上的大量评估显示，LGQAVE 在给出准确的多项选择和开放式答案方面，显著优于现有模型。

> This paper tackles the intricate challenge of video question-answering (VideoQA). Despite notable progress, current methods fall short of effectively integrating questions with video frames and semantic object-level abstractions to create question-aware video representations. We introduce Local-Global Question Aware Video Embedding (LGQAVE), which incorporates three major innovations to integrate multi-modal knowledge better and emphasize semantic visual concepts relevant to specific questions. LGQAVE moves beyond traditional ad-hoc frame sampling by utilizing a cross-attention mechanism that precisely identifies the most relevant frames concerning the questions. It captures the dynamics of objects within these frames using distinct graphs, grounding them in question semantics with the miniGPT model. These graphs are processed by a question-aware dynamic graph transformer (Q-DGT), which refines the outputs to develop nuanced global and local video representations. An additional cross-attention module integrates these local and global embeddings to generate the final video embeddings, which a language model uses to generate answers. Extensive evaluations across multiple benchmarks demonstrate that LGQAVE significantly outperforms existing models in delivering accurate multi-choice and open-ended answers.

[Arxiv](https://arxiv.org/abs/2412.09230)