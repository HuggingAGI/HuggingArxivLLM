# CDW-CoT: 基于聚类距离加权的链式思维推理

发布时间：2025年01月21日

`LLM应用

理由：这篇论文主要讨论了如何通过改进思维链（CoT）提示方法来提升大型语言模型（LLMs）在复杂推理任务中的表现。具体来说，作者提出了聚类距离加权思维链（CDW-CoT）方法，通过结合聚类与提示优化技术，动态生成适配每个数据实例特征的提示。这种方法直接应用于LLMs的推理任务，属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `推理任务`

> CDW-CoT: Clustered Distance-Weighted Chain-of-Thoughts Reasoning

# 摘要

> 大型语言模型（LLMs）通过思维链（CoT）提示在复杂推理任务中表现卓越。然而，现有CoT方法大多采用统一的提示，无论是手动设计还是自动生成，难以应对数据集的多样性需求。为此，我们提出了聚类距离加权思维链（CDW-CoT）方法，通过结合聚类与提示优化技术，动态生成适配每个数据实例特征的提示。该方法首先利用聚类算法将数据集分组，并从中筛选出反映多样性的提示候选池。接着，CDW-CoT为每个聚类训练最优提示概率分布。最后，根据测试实例与聚类中心的距离，动态构建独特的提示概率分布，并从中选择提示进行推理。CDW-CoT在六个数据集（包括常识、符号和数学推理任务）上均优于传统CoT方法。与手动CoT相比，CDW-CoT在LLaMA2（13B）和LLaMA3（8B）上分别实现了25.34%和15.72%的平均准确率提升。

> Large Language Models (LLMs) have recently achieved impressive results in complex reasoning tasks through Chain of Thought (CoT) prompting. However, most existing CoT methods rely on using the same prompts, whether manually designed or automatically generated, to handle the entire dataset. This one-size-fits-all approach may fail to meet the specific needs arising from the diversities within a single dataset. To solve this problem, we propose the Clustered Distance-Weighted Chain of Thought (CDW-CoT) method, which dynamically constructs prompts tailored to the characteristics of each data instance by integrating clustering and prompt optimization techniques. Our method employs clustering algorithms to categorize the dataset into distinct groups, from which a candidate pool of prompts is selected to reflect the inherent diversity within the dataset. For each cluster, CDW-CoT trains the optimal prompt probability distribution tailored to their specific characteristics. Finally, it dynamically constructs a unique prompt probability distribution for each test instance, based on its proximity to cluster centers, from which prompts are selected for reasoning. CDW-CoT consistently outperforms traditional CoT methods across six datasets, including commonsense, symbolic, and mathematical reasoning tasks. Specifically, when compared to manual CoT, CDW-CoT achieves an average accuracy improvement of 25.34% on LLaMA2 (13B) and 15.72% on LLaMA3 (8B).

[Arxiv](https://arxiv.org/abs/2501.12226)