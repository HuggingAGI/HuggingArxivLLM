# 基于连续令牌扩散的生成推荐方法

发布时间：2025年04月16日

`LLM应用` `推荐系统`

> Generative Recommendation with Continuous-Token Diffusion

# 摘要

> 近年来，基于大型语言模型（LLM）的推荐系统（RecSys）应用日益广泛。当前研究主要通过离散空间表示复杂的用户-物品交互，以适应语言模型的固有特性。然而，这种离散化方法存在以下局限：（i）信息在离散化过程中常被压缩；（ii）现实场景中，大量用户和物品的分词与生成受限于有限的词汇量。采用连续数据为提升表达能力提供了有前景的替代方案，尽管这一方法仍处于初期阶段。为解决这一问题，我们提出了一种新型框架DeftRec，该框架整合了	extbf{去噪扩散模型}，使基于LLM的RecSys能够无缝支持连续	extbf{token}作为输入和目标。首先，我们引入了一种强大的分词器，结合屏蔽操作和加性K路架构，用于索引用户和物品，并将其复杂的协作关系捕获到连续的token中。至关重要的是，我们开发了一种去噪扩散模型，通过基于预训练大型语言模型的推理内容进行条件处理，从而在连续域内处理用户偏好。在去噪过程中，我们重新定义目标以包含负交互，从而构建对用户偏好的全面理解，实现有效且准确的推荐生成。最后，给定一个连续token作为输出，推荐可以通过基于评分的检索轻松生成。大量实验表明，所提出的方法具有有效性，DeftRec在传统和新兴的基于LLM的RecSys基准测试中均超越了竞争对手。

> In recent years, there has been a significant trend toward using large language model (LLM)-based recommender systems (RecSys). Current research primarily focuses on representing complex user-item interactions within a discrete space to align with the inherent discrete nature of language models. However, this approach faces limitations due to its discrete nature: (i) information is often compressed during discretization; (ii) the tokenization and generation for the vast number of users and items in real-world scenarios are constrained by a limited vocabulary. Embracing continuous data presents a promising alternative to enhance expressive capabilities, though this approach is still in its early stages. To address this gap, we propose a novel framework, DeftRec, which incorporates \textbf{de}noising di\textbf{f}fusion models to enable LLM-based RecSys to seamlessly support continuous \textbf{t}oken as input and target. First, we introduce a robust tokenizer with a masking operation and an additive K-way architecture to index users and items, capturing their complex collaborative relationships into continuous tokens. Crucially, we develop a denoising diffusion model to process user preferences within continuous domains by conditioning on reasoning content from pre-trained large language model. During the denoising process, we reformulate the objective to include negative interactions, building a comprehensive understanding of user preferences for effective and accurate recommendation generation. Finally, given a continuous token as output, recommendations can be easily generated through score-based retrieval. Extensive experiments demonstrate the effectiveness of the proposed methods, showing that DeftRec surpasses competitive benchmarks, including both traditional and emerging LLM-based RecSys.

[Arxiv](https://arxiv.org/abs/2504.12007)