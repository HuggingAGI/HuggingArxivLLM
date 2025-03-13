# # 教授 LMMs 进行图像质量评分与解释

发布时间：2025年03月12日

`LLM应用` `计算机视觉` `问答系统`

> Teaching LMMs for Image Quality Scoring and Interpreting

# 摘要

> 图像质量评分与解释是图像质量评估（IQA）的两大核心环节。前者量化图像质量，后者则支持描述性问答。传统上，这两个任务是分开处理的。但从人类视觉系统（HVS）和感知-决策整合模型的角度来看，它们密不可分：解释是评分的基础，而评分是解释的概括。因此，在单一模型中融合这两种能力既直观又合理。本文中，我们提出了Q-SiT（质量评分与解释联合教学），这是一个统一的框架，使大型多模态模型（LMMs）能够同时学习图像质量评分与解释。我们通过将传统的IQA数据集转化为问答数据集，并整合人工标注的解释数据来实现这一目标。此外，我们引入了一种高效的评分与解释平衡策略：先在轻量级LMMs上确定最优数据混合比例，再将此比例映射到主要LMMs上进行微调。这一策略不仅缓解了任务干扰，促进了跨任务知识迁移，还显著降低了计算成本。借助这一框架和策略，我们开发了Q-SiT，这是首个能够同时执行图像质量评分与解释任务的模型，以及它的轻量级变体Q-SiT-mini。实验结果表明，Q-SiT在两项任务中均表现出色，具备卓越的泛化能力。了解更多请访问项目页面https://github.com/Q-Future/Q-SiT。


> Image quality scoring and interpreting are two fundamental components of Image Quality Assessment (IQA). The former quantifies image quality, while the latter enables descriptive question answering about image quality. Traditionally, these two tasks have been addressed independently. However, from the perspective of the Human Visual System (HVS) and the Perception-Decision Integration Model, they are inherently interconnected: interpreting serves as the foundation for scoring, while scoring provides an abstract summary of interpreting. Thus, unifying these capabilities within a single model is both intuitive and logically coherent. In this paper, we propose Q-SiT (Quality Scoring and Interpreting joint Teaching), a unified framework that enables large multimodal models (LMMs) to learn both image quality scoring and interpreting simultaneously. We achieve this by transforming conventional IQA datasets into learnable question-answering datasets and incorporating human-annotated quality interpreting data for training. Furthermore, we introduce an efficient scoring & interpreting balance strategy, which first determines the optimal data mix ratio on lightweight LMMs and then maps this ratio to primary LMMs for fine-tuning adjustment. This strategy not only mitigates task interference and enhances cross-task knowledge transfer but also significantly reduces computational costs compared to direct optimization on full-scale LMMs. With this joint learning framework and corresponding training strategy, we develop Q-SiT, the first model capable of simultaneously performing image quality scoring and interpreting tasks, along with its lightweight variant, Q-SiT-mini. Experimental results demonstrate that Q-SiT achieves strong performance in both tasks with superior generalization IQA abilities.Project page at https://github.com/Q-Future/Q-SiT.

[Arxiv](https://arxiv.org/abs/2503.09197)