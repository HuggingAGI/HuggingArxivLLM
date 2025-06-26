# LettinGo: 探索推荐系统中的用户档案生成方法

发布时间：2025年06月23日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在推荐系统中的应用，特别是通过生成多样化和自适应的用户画像来提升推荐系统的性能。研究重点在于将LLMs应用于用户画像生成，属于LLM的实际应用领域。` `推荐系统` `用户画像`

> LettinGo: Explore User Profile Generation for Recommendation System

# 摘要

> 用户画像在推荐系统中扮演着关键角色，它将原始的用户互动数据转化为结构化表达，从而实现个性化推荐。传统基于嵌入的用户画像虽然有效，但缺乏可解释性和灵活性。随着大型语言模型（LLMs）的快速发展，我们得以创建语义更丰富、更透明的文本用户画像。然而，现有方法往往受限于固定的格式，难以全面捕捉用户行为的多样性。本文提出了一种名为LettingGo的全新框架，旨在生成多样化且自适应的用户画像。

我们的方法通过结合LLMs的强大表达能力和下游推荐任务的直接反馈，成功突破了传统监督微调（SFT）的 rigid 约束。我们采用直接偏好优化（DPO）技术，使画像生成与具体任务需求相匹配，确保生成的画像既灵活又有效。LettingGo框架主要分为三个阶段：首先，利用多个LLMs探索多样化的用户画像；其次，通过评估画像在推荐系统中的实际影响来判断其质量；最后，基于任务表现衍生的偏好对数据对齐画像生成过程。

实验结果表明，LettingGo框架显著提升了推荐系统的准确性、灵活性和情境感知能力。这项研究为下一代推荐系统的关键创新——用户画像生成提供了重要突破。


> User profiling is pivotal for recommendation systems, as it transforms raw user interaction data into concise and structured representations that drive personalized recommendations. While traditional embedding-based profiles lack interpretability and adaptability, recent advances with large language models (LLMs) enable text-based profiles that are semantically richer and more transparent. However, existing methods often adhere to fixed formats that limit their ability to capture the full diversity of user behaviors. In this paper, we introduce LettinGo, a novel framework for generating diverse and adaptive user profiles. By leveraging the expressive power of LLMs and incorporating direct feedback from downstream recommendation tasks, our approach avoids the rigid constraints imposed by supervised fine-tuning (SFT). Instead, we employ Direct Preference Optimization (DPO) to align the profile generator with task-specific performance, ensuring that the profiles remain adaptive and effective. LettinGo operates in three stages: (1) exploring diverse user profiles via multiple LLMs, (2) evaluating profile quality based on their impact in recommendation systems, and (3) aligning the profile generation through pairwise preference data derived from task performance. Experimental results demonstrate that our framework significantly enhances recommendation accuracy, flexibility, and contextual awareness. This work enhances profile generation as a key innovation for next-generation recommendation systems.

[Arxiv](https://arxiv.org/abs/2506.18309)