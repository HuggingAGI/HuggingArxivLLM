# 基于深度学习的不一致方法名称识别：我们还有多远？

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了使用深度学习方法来识别函数名与其实现不一致的问题，并提出了使用大语言模型（LLMs）的改进方案。虽然论文涉及了多种深度学习方法，但其核心关注点是如何利用LLMs来改进现有的方法，因此将其归类为“LLM应用”是合适的。` `软件工程`

> Deep Learning-Based Identification of Inconsistent Method Names: How Far Are We?

# 摘要

> 简洁且意义明确的函数名对程序的理解和维护至关重要。然而，函数名可能与其实现不一致，导致混淆和错误。已有多种基于深度学习（DL）的方法被提出用于识别这种不一致性，初步评估结果令人鼓舞。然而，这些评估通常使用平衡数据集，其中不一致和一致的函数名数量相等。这种设置以及数据集构建中的缺陷导致了误报，使得报告的性能在现实场景中不太可靠，因为现实中大多数函数名是一致的。本文通过实证研究评估了最先进的基于深度学习的方法来识别不一致的函数名。我们结合提交历史的自动识别和开发人员的手动检查，创建了一个新的基准，减少了误报。我们在此基准上评估了五种代表性的深度学习方法（一种基于检索的方法和四种基于生成的方法）。结果表明，从平衡数据集转移到新基准时，性能显著下降。我们进一步进行了定量和定性分析，以了解这些方法的优缺点。基于检索的方法在简单函数和具有流行名称子标记的函数上表现良好，但由于表示技术效率低下而失败。基于生成的方法则因相似性计算不准确和名称生成不成熟而表现不佳。基于这些发现，我们提出了使用对比学习和大语言模型（LLMs）的改进方案。研究表明，在将这些深度学习方法有效应用于现实世界的软件系统之前，仍需进行重大改进。

> Concise and meaningful method names are crucial for program comprehension and maintenance. However, method names may become inconsistent with their corresponding implementations, causing confusion and errors. Several deep learning (DL)-based approaches have been proposed to identify such inconsistencies, with initial evaluations showing promising results. However, these evaluations typically use a balanced dataset, where the number of inconsistent and consistent names are equal. This setup, along with flawed dataset construction, leads to false positives, making reported performance less reliable in real-world scenarios, where most method names are consistent. In this paper, we present an empirical study that evaluates state-of-the-art DL-based methods for identifying inconsistent method names. We create a new benchmark by combining automatic identification from commit histories and manual developer inspections, reducing false positives. We evaluate five representative DL approaches (one retrieval-based and four generation-based) on this benchmark. Our results show that performance drops substantially when moving from the balanced dataset to the new benchmark. We further conduct quantitative and qualitative analyses to understand the strengths and weaknesses of the approaches. Retrieval-based methods perform well on simple methods and those with popular name sub-tokens but fail due to inefficient representation techniques. Generation-based methods struggle with inaccurate similarity calculations and immature name generation. Based on these findings, we propose improvements using contrastive learning and large language models (LLMs). Our study suggests that significant improvements are needed before these DL approaches can be effectively applied to real-world software systems.

[Arxiv](https://arxiv.org/abs/2501.12617)