# # RAG-Adapter：助力长视频理解的即插即用式RAG增强框架

发布时间：2025年03月11日

`RAG` `视频理解` `多模态模型`

> RAG-Adapter: A Plug-and-Play RAG-enhanced Framework for Long Video Understanding

# 摘要

> 多模态大语言模型（MLLMs）在视频理解领域正快速发展。为了准确评估这些模型的视频理解能力，Video-MME和MLVU等长视频理解基准测试被提出。然而，这些基准测试直接采用均匀帧采样方式，导致信息大量丢失，影响了评估结果对MLLMs真实能力的准确反映。为解决这一问题，我们提出了RAG-Adapter，一个即插即用的框架，通过采样与问题最相关的帧来减少测试过程中的信息丢失。此外，我们引入了分组监督对比学习（GCL）方法，通过在我们构建的MMAT数据集上进行微调，进一步提升了RAG-Adapter的采样效果。最后，我们在多个视频理解基准测试中对众多基线MLLMs进行了测试，发现RAG-Adapter采样在长视频基准测试中始终优于均匀采样（例如，在Video-MME上，GPT-4o的准确率提高了9.3%），从而提供了一种更准确的测试方法。

> Multi-modal Large Language Models (MLLMs) capable of video understanding are advancing rapidly. To effectively assess their video comprehension capabilities, long video understanding benchmarks, such as Video-MME and MLVU, are proposed. However, these benchmarks directly use uniform frame sampling for testing, which results in significant information loss and affects the accuracy of the evaluations in reflecting the true abilities of MLLMs. To address this, we propose RAG-Adapter, a plug-and-play framework that reduces information loss during testing by sampling frames most relevant to the given question. Additionally, we introduce a Grouped-supervised Contrastive Learning (GCL) method to further enhance sampling effectiveness of RAG-Adapter through fine-tuning on our constructed MMAT dataset. Finally, we test numerous baseline MLLMs on various video understanding benchmarks, finding that RAG-Adapter sampling consistently outperforms uniform sampling (e.g., Accuracy of GPT-4o increases by 9.3 percent on Video-MME), providing a more accurate testing method for long video benchmarks.

[Arxiv](https://arxiv.org/abs/2503.08576)