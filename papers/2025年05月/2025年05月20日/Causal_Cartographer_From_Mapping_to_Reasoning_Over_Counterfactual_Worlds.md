# 因果制图师：从绘制地图到推理反事实世界

发布时间：2025年05月20日

`LLM应用

理由：这篇论文探讨了因果推理在大型语言模型中的应用，提出了一个框架来提升LLMs在因果推理任务中的表现，属于LLM的应用层面。` `因果推理` `机器学习`

> Causal Cartographer: From Mapping to Reasoning Over Counterfactual Worlds

# 摘要

> 因果世界模型能够回答关于特定环境的反事实问题，即预测如果某些事件以不同方式发生，环境会如何演变。这需要理解事件背后的根本原因，并对未知分布进行因果推断。然而，目前基础模型，尤其是大型语言模型（LLMs），尚未展现出超越现有因果关系记忆的因果推理能力。此外，现实世界应用中反事实的评估极具挑战性，因为只有事实世界可观察，这使得评估只能依赖合成数据集。我们通过显式提取和建模因果关系解决了这些问题，并提出了因果制图师（Causal Cartographer）框架。首先，我们引入了一个基于图检索增强生成的代理，用于从数据中提取因果关系。这种方法使我们能够构建一个由真实世界因果关系组成的大网络，作为因果知识库，并用于构建真实世界的反事实。此外，我们创建了一个受因果关系约束的反事实推理代理，以执行可靠的分步因果推断。我们的方法不仅能够提取因果知识，还能够提升LLMs在因果推理任务中的鲁棒性，同时降低推理成本和减少虚假相关性。

> Causal world models are systems that can answer counterfactual questions about an environment of interest, i.e. predict how it would have evolved if an arbitrary subset of events had been realized differently. It requires understanding the underlying causes behind chains of events and conducting causal inference for arbitrary unseen distributions. So far, this task eludes foundation models, notably large language models (LLMs), which do not have demonstrated causal reasoning capabilities beyond the memorization of existing causal relationships. Furthermore, evaluating counterfactuals in real-world applications is challenging since only the factual world is observed, limiting evaluation to synthetic datasets. We address these problems by explicitly extracting and modeling causal relationships and propose the Causal Cartographer framework. First, we introduce a graph retrieval-augmented generation agent tasked to retrieve causal relationships from data. This approach allows us to construct a large network of real-world causal relationships that can serve as a repository of causal knowledge and build real-world counterfactuals. In addition, we create a counterfactual reasoning agent constrained by causal relationships to perform reliable step-by-step causal inference. We show that our approach can extract causal knowledge and improve the robustness of LLMs for causal reasoning tasks while reducing inference costs and spurious correlations.

[Arxiv](https://arxiv.org/abs/2505.14396)