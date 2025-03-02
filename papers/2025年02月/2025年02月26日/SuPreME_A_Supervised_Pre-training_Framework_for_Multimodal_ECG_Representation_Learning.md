# SuPreME: 为多模态心电图表示学习提供了一个监督式预训练框架

发布时间：2025年02月26日

`LLM应用

摘要中提到的研究主要应用大型语言模型（LLMs）来处理ECG报告，提取结构化临床实体，用于构建高质量的数据集，并实现零样本分类。这属于将LLMs应用于医疗领域，因此归类为LLM应用。`

> SuPreME: A Supervised Pre-training Framework for Multimodal ECG Representation Learning

# 摘要

> 心血管疾病是全球死亡和残疾的主要原因之一。心电图（ECG）在诊断和监测心脏健康中至关重要，但获取大规模标注的ECG数据集耗时费力。近期的ECG自监督学习（eSSL）方法虽然通过无需大量标签的学习特征来缓解这一问题，但未能捕捉到细粒度的临床语义，且需要大量任务特定微调。为解决这些问题，我们提出了【数学公式】，一个用于多模态ECG表征学习的监督预训练框架。该框架利用大型语言模型（LLMs）从自由文本的ECG报告中提取结构化临床实体，过滤噪声和不相关内容，增强临床表征学习，并构建高质量、细粒度标注的数据集。通过使用基于文本的心脏查询替代传统分类标签，【数学公式】实现了无需额外微调的零样本分类。我们在涵盖127种心脏状况的六个下游数据集上评估了【数学公式】，其零样本AUC性能比现有最先进的eSSL和多模态方法高出1.96%以上。实验结果证明了【数学公式】在利用结构化临床知识构建高质量ECG表征方面的有效性。所有代码和数据将在接受后公开发布。

> Cardiovascular diseases are a leading cause of death and disability worldwide. Electrocardiogram (ECG) recordings are critical for diagnosing and monitoring cardiac health, but obtaining large-scale annotated ECG datasets is labor-intensive and time-consuming. Recent ECG Self-Supervised Learning (eSSL) methods mitigate this by learning features without extensive labels but fail to capture fine-grained clinical semantics and require extensive task-specific fine-tuning. To address these challenges, we propose $\textbf{SuPreME}$, a $\textbf{Su}$pervised $\textbf{Pre}$-training framework for $\textbf{M}$ultimodal $\textbf{E}$CG representation learning. SuPreME applies Large Language Models (LLMs) to extract structured clinical entities from free-text ECG reports, filter out noise and irrelevant content, enhance clinical representation learning, and build a high-quality, fine-grained labeled dataset. By using text-based cardiac queries instead of traditional categorical labels, SuPreME enables zero-shot classification of unseen diseases without additional fine-tuning. We evaluate SuPreME on six downstream datasets covering 127 cardiac conditions, achieving superior zero-shot AUC performance over state-of-the-art eSSL and multimodal methods by over 1.96\%. Results demonstrate the effectiveness of SuPreME in leveraging structured, clinically relevant knowledge for high-quality ECG representations. All code and data will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2502.19668)