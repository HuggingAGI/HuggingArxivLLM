# 意图驱动的上下文学习用于少样本对话状态追踪

发布时间：2024年12月04日

`LLM应用` `对话系统`

> Intent-driven In-context Learning for Few-shot Dialogue State Tracking

# 摘要

> 对话状态跟踪（DST）在任务导向型对话系统中至关重要。然而，用户输入可能包含隐性信息，这给 DST 任务带来巨大挑战。而且，DST 数据包含复杂信息，不仅有大量与当前轮次无关的噪声，构建 DST 数据集的成本也很高。为应对这些难题，我们引入了用于少样本 DST 的意图驱动的上下文学习（IDIC-DST）。通过提取用户意图，我们提出意图驱动的对话信息增强模块来增强对话信息，从而能更有效地跟踪对话状态。另外，在意图驱动的示例检索模块中，我们屏蔽 DST 数据中的噪声信息并改写用户输入，在此模块中检索相似示例。随后，利用预训练的大型语言模型，借助增强的对话信息和示例来更新对话状态。实验结果显示，IDIC-DST 在 MultiWOZ 2.1 和 MultiWOZ 2.4 数据集的少样本设置中表现达到了最先进水平。

> Dialogue state tracking (DST) plays an essential role in task-oriented dialogue systems. However, user's input may contain implicit information, posing significant challenges for DST tasks. Additionally, DST data includes complex information, which not only contains a large amount of noise unrelated to the current turn, but also makes constructing DST datasets expensive. To address these challenges, we introduce Intent-driven In-context Learning for Few-shot DST (IDIC-DST). By extracting user's intent, we propose an Intent-driven Dialogue Information Augmentation module to augment the dialogue information, which can track dialogue states more effectively. Moreover, we mask noisy information from DST data and rewrite user's input in the Intent-driven Examples Retrieval module, where we retrieve similar examples. We then utilize a pre-trained large language model to update the dialogue state using the augmented dialogue information and examples. Experimental results demonstrate that IDIC-DST achieves state-of-the-art performance in few-shot settings on MultiWOZ 2.1 and MultiWOZ 2.4 datasets.

[Arxiv](https://arxiv.org/abs/2412.03270)