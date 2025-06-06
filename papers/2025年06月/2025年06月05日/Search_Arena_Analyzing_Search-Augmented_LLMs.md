# 搜索增强LLM分析平台：深入解析搜索增强型大语言模型

发布时间：2025年06月05日

`LLM应用

理由：这篇论文主要探讨了搜索增强型语言模型在实际应用中的表现和评估，通过构建大规模数据集分析用户偏好和模型性能，属于LLM的实际应用研究。` `数据科学`

> Search Arena: Analyzing Search-Augmented LLMs

# 摘要

> 搜索增强型语言模型整合了网络搜索与大型语言模型（LLMs），旨在提升回答的相关性和新鲜度。然而，分析这些系统仍具挑战性：现有数据集规模有限且范围狭窄，通常局限于静态、单轮的事实核查问题。本文中，我们推出Search Arena，一个基于众包、大规模、人类偏好数据集，包含24,000多对多轮用户与搜索增强型LLMs的互动。该数据集涵盖了多样化的意图和语言，并包含完整的系统轨迹以及约12,000个人类偏好投票。我们的分析揭示，用户偏好受引用数量影响，即使引用内容不直接支持相关主张，这揭示了感知与实际可信度之间的差距。此外，用户偏好因引用来源而异，表明社区驱动平台通常更受欢迎，而静态百科全书来源并不总是合适且可靠。为了评估不同设置下的性能，我们通过在通用聊天环境和搜索密集型场景中测试搜索增强型LLMs，进行了跨场景分析。我们发现，网络搜索并未降低甚至可能提升非搜索场景下的性能；然而，若仅依赖模型的参数化知识，搜索场景下的质量会受到显著影响。我们已开源该数据集以支持未来研究。我们的数据集和代码可在以下链接获取：https://github.com/lmarena/search-arena。

> Search-augmented language models combine web search with Large Language Models (LLMs) to improve response groundedness and freshness. However, analyzing these systems remains challenging: existing datasets are limited in scale and narrow in scope, often constrained to static, single-turn, fact-checking questions. In this work, we introduce Search Arena, a crowd-sourced, large-scale, human-preference dataset of over 24,000 paired multi-turn user interactions with search-augmented LLMs. The dataset spans diverse intents and languages, and contains full system traces with around 12,000 human preference votes. Our analysis reveals that user preferences are influenced by the number of citations, even when the cited content does not directly support the attributed claims, uncovering a gap between perceived and actual credibility. Furthermore, user preferences vary across cited sources, revealing that community-driven platforms are generally preferred and static encyclopedic sources are not always appropriate and reliable. To assess performance across different settings, we conduct cross-arena analyses by testing search-augmented LLMs in a general-purpose chat environment and conventional LLMs in search-intensive settings. We find that web search does not degrade and may even improve performance in non-search settings; however, the quality in search settings is significantly affected if solely relying on the model's parametric knowledge. We open-sourced the dataset to support future research in this direction. Our dataset and code are available at: https://github.com/lmarena/search-arena.

[Arxiv](https://arxiv.org/abs/2506.05334)