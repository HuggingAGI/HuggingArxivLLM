# # SF2T: 自监督视频大语言模型片段微调实现细粒度理解  
基于自监督学习的视频大语言模型片段微调方法，助力实现更精细的视频理解能力。

发布时间：2025年04月10日

`LLM应用

理由：这篇论文主要探讨了基于视频的大型语言模型（Video-LLMs）在细粒度理解方面的改进，通过自监督片段微调（SF²T）方法和新的基准数据集来提升模型性能。这属于大型语言模型的应用层面，专注于优化和提升模型在特定任务中的表现。` `视频分析` `视频理解`

> SF2T: Self-supervised Fragment Finetuning of Video-LLMs for Fine-Grained Understanding

# 摘要

> 近年来，基于视频的大型语言模型（Video-LLMs）取得了显著进展，这一进步得益于多模态 LLM 的发展。尽管这些模型在视频整体描述方面表现出色，但它们在细粒度理解，尤其是视觉动态和视频细节查询方面仍存在不足。为了解决这些问题，我们发现对 Video-LLMs 进行自监督片段任务的微调，能够显著提升其对视频的细粒度理解能力。因此，我们提出了两项创新性贡献：(1) 自监督片段微调（SF$^2$T），这是一种无需大量标注的新型微调方法，利用视频丰富的内在特性进行训练，同时解锁 Video-LLMs 更精细的理解能力。此外，它还使研究人员摆脱了繁琐的标注工作，并巧妙地规避了自然语言的局限性，后者通常无法捕捉视频中复杂的时空变化；(2) 全新基准数据集 FineVidBench，用于严格评估 Video-LLMs 在场景和片段级别上的性能，全面评估其能力。我们评估了多个模型，并在它们身上验证了 SF$^2$T 的有效性。实验结果表明，我们的方法显著提升了 Video-LLMs 捕捉和解释时空细节的能力。

> Video-based Large Language Models (Video-LLMs) have witnessed substantial advancements in recent years, propelled by the advancement in multi-modal LLMs. Although these models have demonstrated proficiency in providing the overall description of videos, they struggle with fine-grained understanding, particularly in aspects such as visual dynamics and video details inquiries. To tackle these shortcomings, we find that fine-tuning Video-LLMs on self-supervised fragment tasks, greatly improve their fine-grained video understanding abilities. Hence we propose two key contributions:(1) Self-Supervised Fragment Fine-Tuning (SF$^2$T), a novel effortless fine-tuning method, employs the rich inherent characteristics of videos for training, while unlocking more fine-grained understanding ability of Video-LLMs. Moreover, it relieves researchers from labor-intensive annotations and smartly circumvents the limitations of natural language, which often fails to capture the complex spatiotemporal variations in videos; (2) A novel benchmark dataset, namely FineVidBench, for rigorously assessing Video-LLMs' performance at both the scene and fragment levels, offering a comprehensive evaluation of their capabilities. We assessed multiple models and validated the effectiveness of SF$^2$T on them. Experimental results reveal that our approach improves their ability to capture and interpret spatiotemporal details.

[Arxiv](https://arxiv.org/abs/2504.07745)