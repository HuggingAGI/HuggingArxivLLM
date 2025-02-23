# 优化大型多模态模型微调方法，用于仇恨表情包检测

发布时间：2025年02月18日

`LLM应用` `网络空间` `表情包检测`

> Improved Fine-Tuning of Large Multimodal Models for Hateful Meme Detection

# 摘要

> 有害表情包已成为网络空间的重要议题，亟需可靠的自动检测系统。尽管大型多模态模型在各类任务中展现出强大的泛化能力，但面对有害表情包检测任务时，它们却表现不佳，这主要源于表情包内容与新兴社会趋势和突发新闻密切相关，具有动态性。近期研究表明，传统基于监督学习的微调方法在这一领域存在明显局限。针对这些挑战，我们提出了一种名为大语言多模态模型检索引导对比学习（LMM-RGCL）的新型两阶段微调框架，旨在提升模型在领域内准确性和跨领域泛化能力。实验结果表明，在六个广泛使用的表情包分类数据集上，LMM-RGCL实现了当前最优性能，超越了包括VPD-PALI-X-55B在内的基于智能体的系统。此外，该方法在低资源环境下对跨领域有害表情包的泛化能力同样出色，优于GPT-4等模型。

> Hateful memes have become a significant concern on the Internet, necessitating robust automated detection systems. While large multimodal models have shown strong generalization across various tasks, they exhibit poor generalization to hateful meme detection due to the dynamic nature of memes tied to emerging social trends and breaking news. Recent work further highlights the limitations of conventional supervised fine-tuning for large multimodal models in this context. To address these challenges, we propose Large Multimodal Model Retrieval-Guided Contrastive Learning (LMM-RGCL), a novel two-stage fine-tuning framework designed to improve both in-domain accuracy and cross-domain generalization. Experimental results on six widely used meme classification datasets demonstrate that LMM-RGCL achieves state-of-the-art performance, outperforming agent-based systems such as VPD-PALI-X-55B. Furthermore, our method effectively generalizes to out-of-domain memes under low-resource settings, surpassing models like GPT-4o.

[Arxiv](https://arxiv.org/abs/2502.13061)