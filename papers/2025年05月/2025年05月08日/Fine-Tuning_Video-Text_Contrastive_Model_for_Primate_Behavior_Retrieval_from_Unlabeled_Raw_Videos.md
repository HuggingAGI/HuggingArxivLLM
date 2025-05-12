# 微调视频文本对比模型，从无标签原始视频中提取灵长类行为

发布时间：2025年05月08日

`LLM应用` `野生动物研究`

> Fine-Tuning Video-Text Contrastive Model for Primate Behavior Retrieval from Unlabeled Raw Videos

# 摘要

> 非人灵长类动物的自然栖息地视频记录是研究其野外行为的重要资源。我们针对卷尾猴这一特定领域对预训练的视频-文本基础模型进行了微调，目标是开发实用的计算模型，帮助研究人员高效地从视频中检索有用片段。我们专注于一个极具挑战性的问题：仅基于未标注的原始视频片段进行模型训练，有时利用来自野外合作研究者提供的简要音频描述。我们借助多模态大语言模型（MLLMs）和视觉-语言模型（VLMs）的最新进展来应对视频和音频内容极度噪声的特性。具体来说，我们提出了一种创新性方法：结合智能数据处理管道和微调过程。数据处理管道能够自动从原始视频中提取干净且语义对齐的视频-文本对，随后通过低秩适应（LoRA）技术对预训练的微软X-CLIP模型进行微调。在我们的领域数据上，16帧模型的$Hits@5$提升了$167\%$，8帧模型的$Hits@5$提升了$114\%$。此外，根据$NDCG@K$的结果，我们的模型能够很好地对大部分目标行为进行排序，而测试的原始预训练模型则完全无法进行排序。代码将在论文被接收后公开。

> Video recordings of nonhuman primates in their natural habitat are a common source for studying their behavior in the wild. We fine-tune pre-trained video-text foundational models for the specific domain of capuchin monkeys, with the goal of developing useful computational models to help researchers to retrieve useful clips from videos. We focus on the challenging problem of training a model based solely on raw, unlabeled video footage, using weak audio descriptions sometimes provided by field collaborators. We leverage recent advances in Multimodal Large Language Models (MLLMs) and Vision-Language Models (VLMs) to address the extremely noisy nature of both video and audio content. Specifically, we propose a two-folded approach: an agentic data treatment pipeline and a fine-tuning process. The data processing pipeline automatically extracts clean and semantically aligned video-text pairs from the raw videos, which are subsequently used to fine-tune a pre-trained Microsoft's X-CLIP model through Low-Rank Adaptation (LoRA). We obtained an uplift in $Hits@5$ of $167\%$ for the 16 frames model and an uplift of $114\%$ for the 8 frame model on our domain data. Moreover, based on $NDCG@K$ results, our model is able to rank well most of the considered behaviors, while the tested raw pre-trained models are not able to rank them at all. The code will be made available upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.05681)