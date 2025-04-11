# # 大型语言模型在搜索模拟中的类人思维探索

发布时间：2025年04月10日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来模拟用户搜索行为，具体包括生成类人行为如查询、浏览和点击。研究通过监督微调训练LLMs模仿人类的思维和行为，并评估了其在用户模拟中的潜力。因此，该研究属于将LLMs应用于实际任务的范畴。` `信息检索`

> Exploring Human-Like Thinking in Search Simulations with Large Language Models

# 摘要

> 模拟用户搜索行为是信息检索领域的核心任务，可应用于用户行为建模、数据增强和系统评估。大型语言模型（LLMs）的突破性进展为生成类人行为（包括查询、浏览和点击）带来了新的可能性。在本研究中，我们探索了将类人思维融入搜索模拟的方法，通过利用LLMs来模拟用户隐藏的认知过程。具体而言，给定一个搜索任务和上下文，我们引导LLMs先像人类一样思考，然后再执行相应的操作。由于现有搜索数据集未包含用户的思维过程，我们开展了一项用户研究，以收集一个包含用户显式思维的新数据集。我们研究了将类人思维纳入模拟性能的影响，并通过监督微调（SFT）训练LLMs模仿人类的思维和行为。我们的实验从两个维度探索了在用户模拟中使用LLMs的潜力：（1）是否包含显式思维，以及（2）是否在思维增强的数据集上进行微调。实验结果表明，在用户模拟中引入类人思维是可行的，并且具有潜力，尽管在某些指标上的性能提升仍然有限。我们相信，这项研究为在搜索模拟中推进用户行为建模提供了新的思路和启发。

> Simulating user search behavior is a critical task in information retrieval, which can be employed for user behavior modeling, data augmentation, and system evaluation. Recent advancements in large language models (LLMs) have opened up new possibilities for generating human-like actions including querying, browsing, and clicking. In this work, we explore the integration of human-like thinking into search simulations by leveraging LLMs to simulate users' hidden cognitive processes. Specifically, given a search task and context, we prompt LLMs to first think like a human before executing the corresponding action. As existing search datasets do not include users' thought processes, we conducted a user study to collect a new dataset enriched with users' explicit thinking. We investigate the impact of incorporating such human-like thinking on simulation performance and apply supervised fine-tuning (SFT) to teach LLMs to emulate both human thinking and actions. Our experiments span two dimensions in leveraging LLMs for user simulation: (1) with or without explicit thinking, and (2) with or without fine-tuning on the thinking-augmented dataset. The results demonstrate the feasibility and potential of incorporating human-like thinking in user simulations, though performance improvements on some metrics remain modest. We believe this exploration provides new avenues and inspirations for advancing user behavior modeling in search simulations.

[Arxiv](https://arxiv.org/abs/2504.07570)