# InSQuAD：上下文学习借助子模互信息高效检索以保障质量与多样性

发布时间：2025年08月28日

`RAG` `基础理论`

> InSQuAD: In-Context Learning for Efficient Retrieval via Submodular Mutual Information to Enforce Quality and Diversity

# 摘要

> 本文提出InSQuAD，旨在借助子模互信息（SMI）提升上下文学习（ICL）模型的性能，核心在于确保上下文示例兼具质量与多样性。InSQuAD通过两大策略实现这一目标：其一，将ICL任务转化为目标选择问题，提出基于SMI的统一选择策略，挖掘相关且多样的上下文示例，既保证质量又体现多样性；其二，针对现有检索模型只关注查询相关性却忽略多样性（而多样性对ICL至关重要）的常见缺陷，InSQuAD引入组合训练范式，通过全新的基于似然的损失函数学习SMI函数参数，从而在检索模型中兼顾质量与多样性。为进一步助力学习过程，我们用合成生成的复述扩充了现有多跳问答数据集。在九个基准数据集上，采用此策略训练的检索模型结合新的ICL目标选择框架后，性能显著提升，充分验证了我们方法的有效性。

> In this paper, we introduce InSQuAD, designed to enhance the performance of In-Context Learning (ICL) models through Submodular Mutual Information} (SMI) enforcing Quality and Diversity among in-context exemplars. InSQuAD achieves this through two principal strategies: First, we model the ICL task as a targeted selection problem and introduce a unified selection strategy based on SMIs which mines relevant yet diverse in-context examples encapsulating the notions of quality and diversity. Secondly, we address a common pitfall in existing retrieval models which model query relevance, often overlooking diversity, critical for ICL. InSQuAD introduces a combinatorial training paradigm which learns the parameters of an SMI function to enforce both quality and diversity in the retrieval model through a novel likelihood-based loss. To further aid the learning process we augment an existing multi-hop question answering dataset with synthetically generated paraphrases. Adopting the retrieval model trained using this strategy alongside the novel targeted selection formulation for ICL on nine benchmark datasets shows significant improvements validating the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2508.21003)