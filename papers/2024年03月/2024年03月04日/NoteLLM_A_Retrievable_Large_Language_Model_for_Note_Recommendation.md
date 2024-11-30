# NoteLLM，一款专为笔记推荐打造的可检索型大型语言模型。

发布时间：2024年03月04日

`LLM应用`

> NoteLLM: A Retrievable Large Language Model for Note Recommendation

# 摘要

> 现今，在线社区中用户乐于分享自己的生活体验，形成各式各样的“笔记”，因此，如何精准推荐符合用户兴趣的笔记显得尤为重要。现有方法大多仅依赖BERT模型生成笔记的嵌入向量进行相似度比较，但可能忽视了像标签、类别这样能揭示笔记核心内容的关键线索。实际上，通过训练模型生成标签和类别，可以有效提升笔记嵌入的质量，因为两者都能将关键信息浓缩进有限的空间里。值得注意的是，大型语言模型（LLMs）在处理自然语言的理解上已经大大超越了BERT，将其应用于笔记推荐领域显然大有可为。本研究提出了一个名为NoteLLM的新颖统一框架，巧妙利用LLMs解决从一条笔记到另一条笔记（I2I）的推荐问题。具体而言，我们设计了笔记压缩提示技术，将一条笔记紧凑地表示为一个特殊符号，然后采用对比学习的方法获取与其相关的笔记嵌入。不仅如此，我们还通过指令调整让NoteLLM具备摘要生成及自动添加标签/类别的能力。实证研究表明，相比于在线基准方法，我们的方案在真实场景下表现出色，并在小红书的推荐系统中实现了显著优化升级。

> People enjoy sharing "notes" including their experiences within online communities. Therefore, recommending notes aligned with user interests has become a crucial task. Existing online methods only input notes into BERT-based models to generate note embeddings for assessing similarity. However, they may underutilize some important cues, e.g., hashtags or categories, which represent the key concepts of notes. Indeed, learning to generate hashtags/categories can potentially enhance note embeddings, both of which compress key note information into limited content. Besides, Large Language Models (LLMs) have significantly outperformed BERT in understanding natural languages. It is promising to introduce LLMs into note recommendation. In this paper, we propose a novel unified framework called NoteLLM, which leverages LLMs to address the item-to-item (I2I) note recommendation. Specifically, we utilize Note Compression Prompt to compress a note into a single special token, and further learn the potentially related notes' embeddings via a contrastive learning approach. Moreover, we use NoteLLM to summarize the note and generate the hashtag/category automatically through instruction tuning. Extensive validations on real scenarios demonstrate the effectiveness of our proposed method compared with the online baseline and show major improvements in the recommendation system of Xiaohongshu.

[Arxiv](https://arxiv.org/abs/2403.01744)