# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月04日

`RAG

摘要中的研究重点在于将检索增强生成（RAG）与上下文学习相结合，提出了一种新的框架RAICL，用于提升多模态大型语言模型在疾病分类任务中的性能。因此，这篇论文属于RAG类别。` `医学影像分析`

> Retrieval-augmented in-context learning for multimodal large language models in disease classification

# 摘要

> 目标: 本研究致力于通过动态检索信息量丰富的示例，提升多模态大型语言模型（MLLMs）在疾病分类任务中的上下文学习能力。
方法: 我们创新性地提出了一种检索增强的上下文学习（RAICL）框架，将检索增强生成（RAG）与上下文学习（ICL）相结合，能够自适应地筛选出具有相似疾病特征的示例，从而显著提升MLLMs中的ICL效果。具体而言，RAICL通过整合ResNet、BERT、BioBERT和ClinicalBERT等多模态编码器的嵌入信息，精准检索相关示例，并设计优化的对话式提示，使其更适用于上下文学习场景。我们在TCGA和IU胸部X光片两个真实世界多模态数据集上进行了全面评估，测试了包括Qwen、Llava、Gemma等多种MLLMs、不同嵌入策略、相似度度量方法以及示例数量的组合表现。
结果: RAICL在疾病分类任务中展现了显著的性能提升。在TCGA数据集上，准确率从0.7854提升至0.8368；在IU胸部X光片数据集上，准确率从0.7924提升至0.8658。研究发现，多模态输入的表现优于单一模态输入，其中纯文本输入的表现优于仅图像输入。不同模态的信息丰富度决定了最优嵌入模型的选择。少量样本实验表明，增加检索到的示例数量可以进一步提升模型性能。在相似度度量方面，欧氏距离在准确率上表现最佳，而余弦相似度在宏F1分数上更具优势。RAICL在多种MLLMs上均表现出一致的性能提升，证明了其稳健性和广泛的适用性。
结论: RAICL为提升MLLMs在多模态疾病分类任务中的上下文学习能力提供了一种高效且可扩展的解决方案。


> Objectives: We aim to dynamically retrieve informative demonstrations, enhancing in-context learning in multimodal large language models (MLLMs) for disease classification.
  Methods: We propose a Retrieval-Augmented In-Context Learning (RAICL) framework, which integrates retrieval-augmented generation (RAG) and in-context learning (ICL) to adaptively select demonstrations with similar disease patterns, enabling more effective ICL in MLLMs. Specifically, RAICL examines embeddings from diverse encoders, including ResNet, BERT, BioBERT, and ClinicalBERT, to retrieve appropriate demonstrations, and constructs conversational prompts optimized for ICL. We evaluated the framework on two real-world multi-modal datasets (TCGA and IU Chest X-ray), assessing its performance across multiple MLLMs (Qwen, Llava, Gemma), embedding strategies, similarity metrics, and varying numbers of demonstrations.
  Results: RAICL consistently improved classification performance. Accuracy increased from 0.7854 to 0.8368 on TCGA and from 0.7924 to 0.8658 on IU Chest X-ray. Multi-modal inputs outperformed single-modal ones, with text-only inputs being stronger than images alone. The richness of information embedded in each modality will determine which embedding model can be used to get better results. Few-shot experiments showed that increasing the number of retrieved examples further enhanced performance. Across different similarity metrics, Euclidean distance achieved the highest accuracy while cosine similarity yielded better macro-F1 scores. RAICL demonstrated consistent improvements across various MLLMs, confirming its robustness and versatility.
  Conclusions: RAICL provides an efficient and scalable approach to enhance in-context learning in MLLMs for multimodal disease classification.

[Arxiv](https://arxiv.org/abs/2505.02087)