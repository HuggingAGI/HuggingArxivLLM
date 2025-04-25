# 知识蒸馏在基于大型语言模型的包生成中扮演重要角色吗？

发布时间：2025年04月23日

`LLM应用` `软件工程` `系统管理`

> Does Knowledge Distillation Matter for Large Language Model based Bundle Generation?

# 摘要

> LLMs凭借其强大的推理能力和知识储备，正逐渐成为bundle生成领域的热门选择。然而，大规模部署LLMs带来了显著的效率挑战，主要源于其庞大的参数规模导致的微调和推理阶段的高计算成本。知识蒸馏（KD）提供了一个有前景的解决方案，通过将大型教师模型的专业知识转移给紧凑的学生模型。本研究系统性地探索了知识蒸馏在bundle生成中的应用，旨在在保持性能的同时尽可能减少计算需求。我们重点关注三个关键研究问题：（1）知识蒸馏的不同格式如何影响bundle生成性能？（2）蒸馏知识的数量对性能的影响有多大？（3）不同利用蒸馏知识的方式如何影响性能？我们提出了一套全面的KD框架，该框架（i）逐步提取知识（包括模式、规则和深层思考）；（ii）通过不同策略捕获不同数量的蒸馏知识；（iii）结合互补的LLM适应技术（如in-context learning、监督微调、组合方法），将蒸馏知识应用于小型学生模型，以实现特定领域适应和效率提升。大量实验为我们提供了宝贵的见解，揭示了知识格式、数量以及利用方法如何共同影响基于LLM的bundle生成性能，充分展现了KD在实现更高效且有效的基于LLM的bundle生成方面的重要潜力。

> LLMs are increasingly explored for bundle generation, thanks to their reasoning capabilities and knowledge. However, deploying large-scale LLMs introduces significant efficiency challenges, primarily high computational costs during fine-tuning and inference due to their massive parameterization. Knowledge distillation (KD) offers a promising solution, transferring expertise from large teacher models to compact student models. This study systematically investigates knowledge distillation approaches for bundle generation, aiming to minimize computational demands while preserving performance. We explore three critical research questions: (1) how does the format of KD impact bundle generation performance? (2) to what extent does the quantity of distilled knowledge influence performance? and (3) how do different ways of utilizing the distilled knowledge affect performance? We propose a comprehensive KD framework that (i) progressively extracts knowledge (patterns, rules, deep thoughts); (ii) captures varying quantities of distilled knowledge through different strategies; and (iii) exploits complementary LLM adaptation techniques (in-context learning, supervised fine-tuning, combination) to leverage distilled knowledge in small student models for domain-specific adaptation and enhanced efficiency. Extensive experiments provide valuable insights into how knowledge format, quantity, and utilization methodologies collectively shape LLM-based bundle generation performance, exhibiting KD's significant potential for more efficient yet effective LLM-based bundle generation.

[Arxiv](https://arxiv.org/abs/2504.17220)