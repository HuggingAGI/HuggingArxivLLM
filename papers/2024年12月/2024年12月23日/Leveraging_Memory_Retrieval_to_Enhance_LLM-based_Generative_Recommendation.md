# 借助内存检索提升基于 LLM 的生成式推荐

发布时间：2024年12月23日

`LLM应用` `推荐系统` `生成式推荐`

> Leveraging Memory Retrieval to Enhance LLM-based Generative Recommendation

# 摘要

> 利用大型语言模型（LLMs）借助用户 - 项目交互历史来生成项目，已成为生成式推荐领域颇具前景的一种模式。然而，LLMs 有限的上下文窗口常常致使其仅关注近期用户交互，从而忽略了更长历史中所包含的长期兴趣。为应对此挑战，我们提出了一种新颖的自动记忆检索框架（AutoMR），它能够在内存中存储长期兴趣，并从中提取相关信息用于 LLMs 中的下一项生成。在两个真实世界数据集上的大量实验结果表明，我们提出的 AutoMR 框架在利用长期兴趣进行生成式推荐方面成效显著。

> Leveraging Large Language Models (LLMs) to harness user-item interaction histories for item generation has emerged as a promising paradigm in generative recommendation. However, the limited context window of LLMs often restricts them to focusing on recent user interactions only, leading to the neglect of long-term interests involved in the longer histories. To address this challenge, we propose a novel Automatic Memory-Retrieval framework (AutoMR), which is capable of storing long-term interests in the memory and extracting relevant information from it for next-item generation within LLMs. Extensive experimental results on two real-world datasets demonstrate the effectiveness of our proposed AutoMR framework in utilizing long-term interests for generative recommendation.

[Arxiv](https://arxiv.org/abs/2412.17593)