# # 数字网络安全专家：我们已经走了多远？

发布时间：2025年04月16日

`LLM应用` `网络安全` `人工智能`

> The Digital Cybersecurity Expert: How Far Have We Come?

# 摘要

> 大型语言模型（LLMs）在网络安全领域的广泛应用凸显了有效模型选择与评估的重要性。传统评估方法往往忽视了影响性能的关键网络安全知识缺口。为此，我们开发了CSEBenchmark——一个基于345个网络安全专家预期掌握的知识点构建的精细评估框架。借鉴认知科学，这些知识点被划分为事实性、概念性和程序性三类，从而设计出11,050道定制化多项选择题。我们对12款 popular LLMs进行了评估，发现即使表现最佳的模型整体准确率也只有85.42%，尤其在专业工具使用和不常见命令方面存在明显知识缺口。不同LLMs的知识缺口各不相同，同一家族的大型模型在小型模型擅长的知识点上可能表现不佳。通过识别并弥补各LLM的具体知识缺口，我们在三个现有基准测试中针对两个网络安全任务实现了最高84%的错误预测纠正提升。此外，我们对各LLM与特定网络安全角色的知识匹配度评估发现，不同模型更适合不同角色，例如GPT-4o适合谷歌高级情报分析师，Deepseek-V3适合亚马逊隐私工程师。这些发现强调了将LLM选择与不同网络安全角色的具体知识要求相匹配的重要性，以实现最佳性能。

> The increasing deployment of large language models (LLMs) in the cybersecurity domain underscores the need for effective model selection and evaluation. However, traditional evaluation methods often overlook specific cybersecurity knowledge gaps that contribute to performance limitations. To address this, we develop CSEBenchmark, a fine-grained cybersecurity evaluation framework based on 345 knowledge points expected of cybersecurity experts. Drawing from cognitive science, these points are categorized into factual, conceptual, and procedural types, enabling the design of 11,050 tailored multiple-choice questions. We evaluate 12 popular LLMs on CSEBenchmark and find that even the best-performing model achieves only 85.42% overall accuracy, with particular knowledge gaps in the use of specialized tools and uncommon commands. Different LLMs have unique knowledge gaps. Even large models from the same family may perform poorly on knowledge points where smaller models excel. By identifying and addressing specific knowledge gaps in each LLM, we achieve up to an 84% improvement in correcting previously incorrect predictions across three existing benchmarks for two cybersecurity tasks. Furthermore, our assessment of each LLM's knowledge alignment with specific cybersecurity roles reveals that different models align better with different roles, such as GPT-4o for the Google Senior Intelligence Analyst and Deepseek-V3 for the Amazon Privacy Engineer. These findings underscore the importance of aligning LLM selection with the specific knowledge requirements of different cybersecurity roles for optimal performance.

[Arxiv](https://arxiv.org/abs/2504.11783)