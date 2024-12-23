# MARE：需求工程的多智能体协作框架

发布时间：2024年05月06日

`Agent` `软件工程` `人工智能`

> MARE: Multi-Agents Collaboration Framework for Requirements Engineering

# 摘要

> 需求工程（RE）是软件开发流程中至关重要的一环，它负责从利益相关者的需求中提炼出需求规格。深度学习技术在RE的多个任务中已取得显著成效。但要制定出优质的需求规格，需要跨不同任务和角色的通力合作。本文提出了一个名为MARE的创新框架，该框架通过大型语言模型（LLMs）在整个RE流程中的协作来提升效率。MARE将RE流程细化为需求引出、建模、验证和规格化四个子任务，每个任务由特定代理执行，且每个代理能执行多项操作。MARE包含五个代理和九种操作。为促进代理间的合作，MARE特别设计了一个工作空间，以便代理上传中间需求工件并获取所需信息。我们在五个公开案例、一个数据集以及本研究创造的四个新案例上进行了实验，并使用三个通用指标与三个基线模型进行了比较。实验结果显示，MARE在生成正确需求模型方面更胜一筹，性能提升了15.4%。此外，我们还对生成的需求规格进行了人工评估，并从三个方面提供了质量分析的深刻见解。

> Requirements Engineering (RE) is a critical phase in the software development process that generates requirements specifications from stakeholders' needs. Recently, deep learning techniques have been successful in several RE tasks. However, obtaining high-quality requirements specifications requires collaboration across multiple tasks and roles. In this paper, we propose an innovative framework called MARE, which leverages collaboration among large language models (LLMs) throughout the entire RE process. MARE divides the RE process into four tasks: elicitation, modeling, verification, and specification. Each task is conducted by engaging one or two specific agents and each agent can conduct several actions. MARE has five agents and nine actions. To facilitate collaboration between agents, MARE has designed a workspace for agents to upload their generated intermediate requirements artifacts and obtain the information they need. We conduct experiments on five public cases, one dataset, and four new cases created by this work. We compared MARE with three baselines using three widely used metrics for the generated requirements models. Experimental results show that MARE can generate more correct requirements models and outperform the state-of-the-art approaches by 15.4%. For the generated requirements specifications, we conduct a human evaluation in three aspects and provide insights about the quality

[Arxiv](https://arxiv.org/abs/2405.03256)