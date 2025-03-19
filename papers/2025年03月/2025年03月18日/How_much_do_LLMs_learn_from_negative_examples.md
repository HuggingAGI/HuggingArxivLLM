# 大型语言模型（LLMs）从反面例子中能学到多少？

发布时间：2025年03月18日

`LLM理论` `问答系统`

> How much do LLMs learn from negative examples?

# 摘要

> 大型语言模型（LLMs）的训练分为三个阶段：无监督预训练、有监督微调（SFT）和基于人类反馈的学习（RLHF/DPO）。值得注意的是，只有在最后一个阶段，模型才会接触到负例——即针对查询的不正确、被拒绝或次优的回复。本文深入研究了负例在LLMs训练中的作用，通过在多项选择题问答基准测试中使用似然比（Likra）模型，精确控制负例的影响和数量。我们的研究结果揭示了三个关键发现：（1）在训练过程中的一个关键阶段，引入负例的Likra每训练一个示例能带来显著更大的提升，与仅使用正例的SFT相比，这使得Likra的学习曲线出现了一个急剧的跳跃，而SFT则表现为平滑渐进的提升；（2）那些看似合理但实际错误的负例（即"近似错误"）具有更大的影响力；（3）虽然仅使用正例的训练无法显著降低合理但错误答案的概率，但引入负例的训练能更准确地识别出这些错误。这些结果表明，负例在提升LLMs的准确性和减少幻觉方面可能具有重要作用。

> Large language models (LLMs) undergo a three-phase training process: unsupervised pre-training, supervised fine-tuning (SFT), and learning from human feedback (RLHF/DPO). Notably, it is during the final phase that these models are exposed to negative examples -- incorrect, rejected, or suboptimal responses to queries. This paper delves into the role of negative examples in the training of LLMs, using a likelihood-ratio (Likra) model on multiple-choice question answering benchmarks to precisely manage the influence and the volume of negative examples. Our findings reveal three key insights: (1) During a critical phase in training, Likra with negative examples demonstrates a significantly larger improvement per training example compared to SFT using only positive examples. This leads to a sharp jump in the learning curve for Likra unlike the smooth and gradual improvement of SFT; (2) negative examples that are plausible but incorrect (near-misses) exert a greater influence; and (3) while training with positive examples fails to significantly decrease the likelihood of plausible but incorrect answers, training with negative examples more accurately identifies them. These results indicate a potentially significant role for negative examples in improving accuracy and reducing hallucinations for LLMs.

[Arxiv](https://arxiv.org/abs/2503.14391)