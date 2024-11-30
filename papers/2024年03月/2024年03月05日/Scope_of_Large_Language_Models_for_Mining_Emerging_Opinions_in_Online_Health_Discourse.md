# 探究大型语言模型在揭示在线健康讨论中新兴观点方面的潜力及应用范围

发布时间：2024年03月05日

`LLM应用`

> Scope of Large Language Models for Mining Emerging Opinions in Online Health Discourse

# 摘要

> 本文提出了一种运用LLM技术的创新框架，用于在线健康社区新兴观点挖掘的整理与评估。我们将这一挑战转化为在Reddit上的（标题，评论）对间进行成对立场检测问题，其中标题蕴含了非预设话题下的新兴健康主张，无论这些主张是明示还是暗示的。具体而言，我们详述了两种方法：(i) 发现并识别标题中是否包含主张的方法；(ii) 基于LLM的、以观点挖掘为核心的立场检测评估方案。为了促进研究，我们发布了首个专门针对长期COVID治疗相关讨论的立场检测数据集——LC-stance，它可用于检验LLM在识别在线健康社区内主张及检测立场方面的性能。鉴于长期COVID作为一种新兴且治疗指导尚不明确的后COVID综合症，适合作为本任务的应用实例。实验证明，GPT-4在未经训练的零样本立场检测任务上显著超越了以往的工作。此外，我们还对LLM模型进行了细致的诊断分析，发现主张类型（显式或隐式）和评论长度是影响模型误差的重要因素。

> In this paper, we develop an LLM-powered framework for the curation and evaluation of emerging opinion mining in online health communities. We formulate emerging opinion mining as a pairwise stance detection problem between (title, comment) pairs sourced from Reddit, where post titles contain emerging health-related claims on a topic that is not predefined. The claims are either explicitly or implicitly expressed by the user. We detail (i) a method of claim identification -- the task of identifying if a post title contains a claim and (ii) an opinion mining-driven evaluation framework for stance detection using LLMs.
  We facilitate our exploration by releasing a novel test dataset, Long COVID-Stance, or LC-stance, which can be used to evaluate LLMs on the tasks of claim identification and stance detection in online health communities. Long Covid is an emerging post-COVID disorder with uncertain and complex treatment guidelines, thus making it a suitable use case for our task. LC-Stance contains long COVID treatment related discourse sourced from a Reddit community. Our evaluation shows that GPT-4 significantly outperforms prior works on zero-shot stance detection. We then perform thorough LLM model diagnostics, identifying the role of claim type (i.e. implicit vs explicit claims) and comment length as sources of model error.

[Arxiv](https://arxiv.org/abs/2403.03336)