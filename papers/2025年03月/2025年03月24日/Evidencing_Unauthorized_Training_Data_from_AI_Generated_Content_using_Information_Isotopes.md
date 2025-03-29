# 利用信息同位素从AI生成内容中发现未经授权的训练数据

发布时间：2025年03月24日

`LLM应用

理由：这篇论文提出了一种新的方法来检测不透明AI系统中未经授权的数据使用，属于大语言模型的应用层面，探讨了如何利用模型生成的内容进行数据追踪和取证。` `数据安全` `隐私保护`

> Evidencing Unauthorized Training Data from AI Generated Content using Information Isotopes

# 摘要

> 鉴于缩放法则，众多 AI 机构正致力于在优质人类数据基础上构建先进 AI。然而，在竞争压力下，部分机构可能在不知情甚至有意情况下将未经授权数据用于 AI 训练，侵犯数据权益。更令人担忧的是，这些 AI 服务依赖不透明云平台，限制了训练和推理过程中的信息访问，仅有生成输出可用于取证。尽管各国已建立法律框架保护数据权益，但在现代不透明 AI 应用中揭示数据滥用证据仍具挑战。本文受同位素追踪化学反应中元素的启发，提出信息同位素概念，并阐述其在追踪不透明 AI 系统训练数据中的特性。我们还提出了一种信息同位素追踪方法，通过检测 AI 生成内容中目标信息同位素的存在，识别并提供未经授权数据使用的证据。我们在十种 AI 模型（包括 GPT-4o、Claude-3.5 和 DeepSeek）和四个关键领域（医疗数据、版权书籍和新闻）的基准数据集上进行了实验。结果显示，通过检查与研究论文长度相当的数据条目，我们的方法能够以 99\% 的准确率和显著证据（p-value$<0.001$）区分训练数据集与非训练数据集。研究结果表明，我们的方法有望成为一种通用工具，赋能包括非 AI 专家在内的个人，在 AI 快速发展的时代保护其数据权益。

> In light of scaling laws, many AI institutions are intensifying efforts to construct advanced AIs on extensive collections of high-quality human data. However, in a rush to stay competitive, some institutions may inadvertently or even deliberately include unauthorized data (like privacy- or intellectual property-sensitive content) for AI training, which infringes on the rights of data owners. Compounding this issue, these advanced AI services are typically built on opaque cloud platforms, which restricts access to internal information during AI training and inference, leaving only the generated outputs available for forensics. Thus, despite the introduction of legal frameworks by various countries to safeguard data rights, uncovering evidence of data misuse in modern opaque AI applications remains a significant challenge. In this paper, inspired by the ability of isotopes to trace elements within chemical reactions, we introduce the concept of information isotopes and elucidate their properties in tracing training data within opaque AI systems. Furthermore, we propose an information isotope tracing method designed to identify and provide evidence of unauthorized data usage by detecting the presence of target information isotopes in AI generations. We conduct experiments on ten AI models (including GPT-4o, Claude-3.5, and DeepSeek) and four benchmark datasets in critical domains (medical data, copyrighted books, and news). Results show that our method can distinguish training datasets from non-training datasets with 99\% accuracy and significant evidence (p-value$<0.001$) by examining a data entry equivalent in length to a research paper. The findings show the potential of our work as an inclusive tool for empowering individuals, including those without expertise in AI, to safeguard their data rights in the rapidly evolving era of AI advancements and applications.

[Arxiv](https://arxiv.org/abs/2503.20800)