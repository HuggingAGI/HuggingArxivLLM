# 评估基于LLM的数据增强在检索任务中的有效性与可扩展性

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Evaluating the Effectiveness and Scalability of LLM-Based Data Augmentation for Retrieval

# 摘要

> 紧凑型双编码器模型凭借高效与可扩展的优势，在检索领域应用广泛。然而，与基于大型语言模型（LLM）的检索模型相比，这类模型性能常显不足，这很可能是因为其世界知识储备有限。尽管基于LLM的数据增强被视作缩小性能差距的策略，但人们对其在实际检索问题中的有效性与可扩展性仍缺乏深入理解。现有研究尚未系统探究关键影响因素，如最佳增强规模、大型增强模型的必要性，以及多样化增强能否提升泛化能力——尤其是在分布外（OOD）场景下。本研究针对检索任务中LLM增强的有效性展开全面探究，涵盖了100多种不同的检索模型、增强模型及增强策略实验设置。研究发现，增强虽能提升检索性能，但超过特定规模后，即便采用多样化增强策略，其增益也会逐渐减弱。意外的是，我们发现使用较小的LLM进行增强，性能可与大型增强模型相媲美。此外，我们还探究了增强效果随检索模型预训练程度的变化，结果显示增强对预训练不足的模型帮助最大。这些发现为更明智、高效的增强策略奠定了基础，有助于在提升成本效益的同时，通过科学决策最大化检索性能。本研究的代码及增强数据集已在https://aka.ms/DAGR公开。

> Compact dual-encoder models are widely used for retrieval owing to their efficiency and scalability. However, such models often underperform compared to their Large Language Model (LLM)-based retrieval counterparts, likely due to their limited world knowledge. While LLM-based data augmentation has been proposed as a strategy to bridge this performance gap, there is insufficient understanding of its effectiveness and scalability to real-world retrieval problems. Existing research does not systematically explore key factors such as the optimal augmentation scale, the necessity of using large augmentation models, and whether diverse augmentations improve generalization, particularly in out-of-distribution (OOD) settings. This work presents a comprehensive study of the effectiveness of LLM augmentation for retrieval, comprising over 100 distinct experimental settings of retrieval models, augmentation models and augmentation strategies. We find that, while augmentation enhances retrieval performance, its benefits diminish beyond a certain augmentation scale, even with diverse augmentation strategies. Surprisingly, we observe that augmentation with smaller LLMs can achieve performance competitive with larger augmentation models. Moreover, we examine how augmentation effectiveness varies with retrieval model pre-training, revealing that augmentation provides the most benefit to models which are not well pre-trained. Our insights pave the way for more judicious and efficient augmentation strategies, thus enabling informed decisions and maximizing retrieval performance while being more cost-effective. Code and augmented datasets accompanying this work are publicly available at https://aka.ms/DAGR.

[Arxiv](https://arxiv.org/abs/2509.16442)