# 探索大型语言模型于问题分类：基于扩展数据与新模型的再探

发布时间：2025年05月30日

`LLM应用` `软件工程` `问题分类`

> Applying Large Language Models to Issue Classification: Revisiting with Extended Data and New Models

# 摘要

> 在软件工程中，有效的问题报告优先级排序有助于优化资源分配和信息恢复。然而，手动分类问题耗时费力，且不具备可扩展性。作为一种替代方案，许多开源软件（OSS）项目采用了自动化方法来完成这项任务，但这种方法通常依赖于大量数据集进行充分训练。传统上，机器学习技术被用于问题分类。最近，大型语言模型（LLMs）作为一种强大的工具，被用于解决一系列软件工程挑战，包括代码和测试生成、将新需求映射到遗留软件端点以及进行代码审查。本研究探讨了基于LLMs的问题分类自动化方法。通过利用这些模型的能力，我们旨在开发一个强大的系统，用于优先级排序问题报告，减少对大量训练数据的依赖，同时保持分类的可靠性。在我们的研究中，我们选择了两个最突出的大型语言模型，开发了一种基于LLMs的解决方案，以准确标注问题。然后，我们比较了它们在多个数据集上的性能。我们的研究结果表明，GPT-4o在分类NLBSE 2024竞赛中的问题表现最佳。此外，GPT-4o在NLBSE 2023竞赛数据集上的表现优于DeepSeek R1，当两个模型在相同的数据集上进行训练时，GPT-4o的F1分数比DeepSeek R1高出20%，而该数据集是NLBSE 2024数据集的十倍大。经过微调的GPT-4o模型平均F1得分为80.7%，而经过微调的DeepSeek R1模型得分为59.33%。增加数据集的大小并未提高F1分数，从而减少了构建高效问题分类解决方案对大规模数据集的依赖。

> Effective prioritization of issue reports in software engineering helps to optimize resource allocation and information recovery. However, manual issue classification is laborious and lacks scalability. As an alternative, many open source software (OSS) projects employ automated processes for this task, yet this method often relies on large datasets for adequate training. Traditionally, machine learning techniques have been used for issue classification. More recently, large language models (LLMs) have emerged as powerful tools for addressing a range of software engineering challenges, including code and test generation, mapping new requirements to legacy software endpoints, and conducting code reviews. The following research investigates an automated approach to issue classification based on LLMs. By leveraging the capabilities of such models, we aim to develop a robust system for prioritizing issue reports, mitigating the necessity for extensive training data while also maintaining reliability in classification. In our research, we developed an LLM-based approach for accurately labeling issues by selecting two of the most prominent large language models. We then compared their performance across multiple datasets. Our findings show that GPT-4o achieved the best results in classifying issues from the NLBSE 2024 competition. Moreover, GPT-4o outperformed DeepSeek R1, achieving an F1 score 20% higher when both models were trained on the same dataset from the NLBSE 2023 competition, which was ten times larger than the NLBSE 2024 dataset. The fine-tuned GPT-4o model attained an average F1 score of 80.7%, while the fine-tuned DeepSeek R1 model achieved 59.33%. Increasing the dataset size did not improve the F1 score, reducing the dependence on massive datasets for building an efficient solution to issue classification.

[Arxiv](https://arxiv.org/abs/2506.00128)