# LLMs 能否胜任心理评估？借助自适应 RAG，通过心理测量实践实现可解释的心理健康筛查

发布时间：2025年01月01日

`RAG

**理由**：
- 该论文提出了一种基于**检索增强生成（RAG）**的方法，通过检索社交媒体帖子并结合大型语言模型（LLMs）来预测心理问卷得分。
- RAG 的核心思想是通过检索外部信息来增强生成模型的性能，而本文正是利用了这一技术来解决心理学问卷预测问题。
- 虽然涉及 LLM 的应用，但其核心创新点在于 RAG 方法的引入，因此更适合归类为 **RAG**。` `心理学` `社交媒体`

> Are LLMs effective psychological assessors? Leveraging adaptive RAG for interpretable mental health screening through psychometric practice

# 摘要

> 在心理学实践中，标准化问卷是评估心理构念（如态度、特质和情绪）的重要工具。随着社交媒体平台的普及，研究人员开始探索利用用户分享的数据进行快速心理健康筛查的计算方法。本研究提出了一种新颖的自适应检索增强生成（RAG）方法，通过分析社交媒体帖子来完成心理问卷。该方法为每个问题检索最相关的用户帖子，并利用大型语言模型（LLMs）在零-shot 设置下预测问卷得分。我们的研究有两个主要发现：首先，该方法能够有效预测用户对心理问卷（如贝克抑郁量表II，BDI-II）的反应，在基于Reddit的基准数据集上表现优异，甚至超越现有模型，且无需训练数据。其次，该方法可推广为一种可扩展的筛查工具，通过完成标准化问卷并跟踪个体项目反应对诊断的贡献，系统得出最终评估，符合心理测量实践。

> In psychological practice, standardized questionnaires serve as essential tools for assessing mental constructs (e.g., attitudes, traits, and emotions) through structured questions (aka items). With the increasing prevalence of social media platforms where users share personal experiences and emotions, researchers are exploring computational methods to leverage this data for rapid mental health screening. In this study, we propose a novel adaptive Retrieval-Augmented Generation (RAG) approach that completes psychological questionnaires by analyzing social media posts. Our method retrieves the most relevant user posts for each question in a psychological survey and uses Large Language Models (LLMs) to predict questionnaire scores in a zero-shot setting. Our findings are twofold. First we demonstrate that this approach can effectively predict users' responses to psychological questionnaires, such as the Beck Depression Inventory II (BDI-II), achieving performance comparable to or surpassing state-of-the-art models on Reddit-based benchmark datasets without relying on training data. Second, we show how this methodology can be generalized as a scalable screening tool, as the final assessment is systematically derived by completing standardized questionnaires and tracking how individual item responses contribute to the diagnosis, aligning with established psychometric practices.

[Arxiv](https://arxiv.org/abs/2501.00982)