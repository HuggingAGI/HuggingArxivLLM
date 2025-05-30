# GateNLP参加 SemEval-2025 任务10：针对多语言叙事分类的分层三步提示方法

发布时间：2025年05月28日

`LLM应用` `信息分类`

> GateNLP at SemEval-2025 Task 10: Hierarchical Three-Step Prompting for Multilingual Narrative Classification

# 摘要

> 在线新闻的普及和虚假信息的快速传播，使得强大的数据分析方法变得至关重要。叙述分类正在成为一个重要的任务，因为识别网络上正在讨论的内容对于事实核查人员、政策制定者和其他从事信息研究的专业人士来说至关重要。本文介绍了我们对SemEval 2025任务10子任务2的解决方案，旨在将新闻文章分类到一个多语言预定义的两层叙述 taxonomy 中，包括主要叙述和子叙述。

我们提出了多语言叙述分类的分层三步提示方法（H3Prompt）。我们的方法遵循三步大型语言模型（LLM）提示策略，其中模型首先将文章分类到两个领域之一（乌克兰-俄罗斯战争或气候变化），然后识别最相关的主要叙述，最后分配子叙述。我们的方法在英语测试集上取得了第一名的成绩，领先于全球28支参赛队伍。代码可在https://github.com/GateNLP/H3Prompt获取。

> The proliferation of online news and the increasing spread of misinformation necessitate robust methods for automatic data analysis. Narrative classification is emerging as a important task, since identifying what is being said online is critical for fact-checkers, policy markers and other professionals working on information studies. This paper presents our approach to SemEval 2025 Task 10 Subtask 2, which aims to classify news articles into a pre-defined two-level taxonomy of main narratives and sub-narratives across multiple languages.
  We propose Hierarchical Three-Step Prompting (H3Prompt) for multilingual narrative classification. Our methodology follows a three-step Large Language Model (LLM) prompting strategy, where the model first categorises an article into one of two domains (Ukraine-Russia War or Climate Change), then identifies the most relevant main narratives, and finally assigns sub-narratives. Our approach secured the top position on the English test set among 28 competing teams worldwide. The code is available at https://github.com/GateNLP/H3Prompt.

[Arxiv](https://arxiv.org/abs/2505.22867)