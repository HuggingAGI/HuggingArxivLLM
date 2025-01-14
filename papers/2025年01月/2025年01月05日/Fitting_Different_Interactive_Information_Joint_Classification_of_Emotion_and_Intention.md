# # 融合多样交互信息：情感与意图的联合分类

发布时间：2025年01月05日

`其他

理由：这篇论文主要关注的是低资源多模态情感与意图识别，虽然涉及了模型训练和数据利用，但并没有明确提到大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等概念。因此，它不属于Agent、RAG、LLM应用或LLM理论中的任何一个分类，更适合归类为其他。` `情感分析` `意图识别`

> Fitting Different Interactive Information: Joint Classification of Emotion and Intention

# 摘要

> 本文是 ICASSP MEIJU@2025 Track I 的冠军方案，专注于低资源多模态情感与意图识别。比赛的关键在于如何高效利用大量未标注数据，并确保不同难度任务在交互阶段的相互促进。我们通过在已标注数据训练的模型上进行伪标签标注，筛选高置信度样本及其标签，缓解了低资源问题。同时，利用实验中发现的意图识别易于表示的特点，使其在不同注意力头下与情感识别相互促进，并通过融合提升了意图识别性能。最终，在精细化处理的数据下，我们在测试集上取得了 0.5532 的高分，成功夺冠。

> This paper is the first-place solution for ICASSP MEIJU@2025 Track I, which focuses on low-resource multimodal emotion and intention recognition. How to effectively utilize a large amount of unlabeled data, while ensuring the mutual promotion of different difficulty levels tasks in the interaction stage, these two points become the key to the competition. In this paper, pseudo-label labeling is carried out on the model trained with labeled data, and samples with high confidence and their labels are selected to alleviate the problem of low resources. At the same time, the characteristic of easy represented ability of intention recognition found in the experiment is used to make mutually promote with emotion recognition under different attention heads, and higher performance of intention recognition is achieved through fusion. Finally, under the refined processing data, we achieve the score of 0.5532 in the Test set, and win the championship of the track.

[Arxiv](https://arxiv.org/abs/2501.06215)