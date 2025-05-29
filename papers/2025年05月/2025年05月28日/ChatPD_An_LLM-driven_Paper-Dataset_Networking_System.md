# ChatPD：由LLM驱动的论文与数据集网络系统，构建智能化研究网络。

发布时间：2025年05月28日

`LLM应用` `学术研究` `数据集管理`

> ChatPD: An LLM-driven Paper-Dataset Networking System

# 摘要

> 科学研究在方法验证方面离不开合适的数据集，但现有的学术平台（如PapersWithCode）在数据集管理方面存在手动工作流程效率低下的问题。为了解决这一瓶颈，我们提出了一种名为ChatPD的系统，该系统利用大型语言模型（LLMs）从学术论文中自动提取数据集信息，并构建结构化的论文-数据集网络。

我们的系统包含三个关键模块：	extit{论文收集}、	extit{数据集信息提取}和	extit{数据集实体解析}，用于构建论文-数据集网络。具体来说，我们提出了一种	extit{图补全与推理}策略，用于将数据集描述映射到其对应的数据集实体。

通过广泛的实验，我们证明ChatPD不仅在数据集使用提取方面优于现有的PapersWithCode平台，还在实体解析任务中实现了约90%的精确率和召回率。此外，我们已部署ChatPD以持续提取论文中使用的数据集，并提供数据集发现服务，例如特定任务的数据集查询和相似数据集推荐。

我们开源了ChatPD以及当前的论文-数据集网络至这个[GitHub仓库]{https://github.com/ChatPD-web/ChatPD}。

> Scientific research heavily depends on suitable datasets for method validation, but existing academic platforms with dataset management like PapersWithCode suffer from inefficiencies in their manual workflow. To overcome this bottleneck, we present a system, called ChatPD, that utilizes Large Language Models (LLMs) to automate dataset information extraction from academic papers and construct a structured paper-dataset network. Our system consists of three key modules: \textit{paper collection}, \textit{dataset information extraction}, and \textit{dataset entity resolution} to construct paper-dataset networks. Specifically, we propose a \textit{Graph Completion and Inference} strategy to map dataset descriptions to their corresponding entities. Through extensive experiments, we demonstrate that ChatPD not only outperforms the existing platform PapersWithCode in dataset usage extraction but also achieves about 90\% precision and recall in entity resolution tasks. Moreover, we have deployed ChatPD to continuously extract which datasets are used in papers, and provide a dataset discovery service, such as task-specific dataset queries and similar dataset recommendations. We open source ChatPD and the current paper-dataset network on this [GitHub repository]{https://github.com/ChatPD-web/ChatPD}.

[Arxiv](https://arxiv.org/abs/2505.22349)