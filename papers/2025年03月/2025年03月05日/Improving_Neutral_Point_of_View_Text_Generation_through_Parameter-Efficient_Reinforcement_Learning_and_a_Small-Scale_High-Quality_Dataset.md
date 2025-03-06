# 通过参数高效强化学习和小型高质量数据集改进中立观点文本生成

发布时间：2025年03月05日

`LLM应用` `生成式AI` `数据集构建`

> Improving Neutral Point of View Text Generation through Parameter-Efficient Reinforcement Learning and a Small-Scale High-Quality Dataset

# 摘要

> 本文介绍了一个数据集的构建与训练方法的评估，旨在提升生成式大语言模型（LLMs）在敏感话题上以中立视角（NPOV）回答问题的能力，使其能够提供更丰富、多样且公正的答案。该数据集名为SHQ-NPOV，包含300个高质量的人工编写的四元组：一个关于敏感话题的查询、一个答案、一个NPOV评分以及一组指向详细阐述各种观点的源文本链接。

本文的两大核心贡献在于：首先，提出了一种通过迭代的人工互评和标注员培训来创建此类数据集的新方法，并将其与数据集一同发布；其次，发现了一种高效参数强化学习（PE-RL）的训练方案，能够显著提升NPOV生成能力。我们对PE-RL与多个基线进行了全面比较和评估，包括LoRA微调（一个强大的基线）、SFT和RLHF。

实验结果表明，PE-RL不仅在整体NPOV质量上优于最强基线（97.06%→99.08%），还在语言学家识别的关键特征上表现更优，这些特征用于区分优秀答案与最佳答案（支持性细节的存在：60.25%→85.21%， oversimplification的缺失：68.74%→91.43%）。定性分析进一步证实了这一结论。此外，我们的评估发现，无论是训练数据集主题还是独立评估主题，结果均无显著差异，这表明我们的PE-RL训练方法具有非常强大的跨主题泛化能力。

> This paper describes the construction of a dataset and the evaluation of training methods to improve generative large language models' (LLMs) ability to answer queries on sensitive topics with a Neutral Point of View (NPOV), i.e., to provide significantly more informative, diverse and impartial answers. The dataset, the SHQ-NPOV dataset, comprises 300 high-quality, human-written quadruplets: a query on a sensitive topic, an answer, an NPOV rating, and a set of links to source texts elaborating the various points of view. The first key contribution of this paper is a new methodology to create such datasets through iterative rounds of human peer-critique and annotator training, which we release alongside the dataset. The second key contribution is the identification of a highly effective training regime for parameter-efficient reinforcement learning (PE-RL) to improve NPOV generation. We compare and extensively evaluate PE-RL and multiple baselines-including LoRA finetuning (a strong baseline), SFT and RLHF.
  PE-RL not only improves on overall NPOV quality compared to the strongest baseline ($97.06\%\rightarrow 99.08\%$), but also scores much higher on features linguists identify as key to separating good answers from the best answers ($60.25\%\rightarrow 85.21\%$ for presence of supportive details, $68.74\%\rightarrow 91.43\%$ for absence of oversimplification). A qualitative analysis corroborates this. Finally, our evaluation finds no statistical differences between results on topics that appear in the training dataset and those on separated evaluation topics, which provides strong evidence that our approach to training PE-RL exhibits very effective out of topic generalization.

[Arxiv](https://arxiv.org/abs/2503.03654)