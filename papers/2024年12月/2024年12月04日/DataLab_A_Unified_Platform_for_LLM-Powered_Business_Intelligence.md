# DataLab：一个用于 LLM 驱动的商业智能的统一平台

发布时间：2024年12月04日

`LLM应用` `商业智能` `数据处理`

> DataLab: A Unified Platform for LLM-Powered Business Intelligence

# 摘要

> 商业智能（BI）能将现代组织中的海量数据转化为切实可行的见解，助力明智决策。近来，基于大型语言模型（LLM）的代理，依据自然语言（NL）查询在可执行环境中自动进行任务规划、推理和行动，从而简化了 BI 工作流程。然而，现有的方法多聚焦于单个 BI 任务，像 NL2SQL 和 NL2VIS 等。由于 BI 具有迭代和协作的特性，不同数据角色和工具间的任务分散，导致效率低下和潜在错误。在本文中，我们推出了 DataLab，这是一个统一的 BI 平台，它将一站式基于 LLM 的代理框架与增强型计算笔记本界面相融合。DataLab 在单一环境中无缝衔接 LLM 辅助与用户定制，为不同数据角色提供了广泛的 BI 任务支持。为达成这种统一，我们设计了针对企业特定 BI 任务定制的领域知识整合模块、促进 BI 工作流程中信息共享的代理间通信机制，以及基于单元格的上下文管理策略，以提升 BI 笔记本中的上下文利用效率。大量实验表明，DataLab 在流行研究基准的各类 BI 任务中均达到了顶尖性能。此外，DataLab 在腾讯的真实世界数据集中保持了高效性和有效性，在企业特定的 BI 任务上，准确率最高提升 58.58%，令牌成本最多降低 61.65%。

> Business intelligence (BI) transforms large volumes of data within modern organizations into actionable insights for informed decision-making. Recently, large language model (LLM)-based agents have streamlined the BI workflow by automatically performing task planning, reasoning, and actions in executable environments based on natural language (NL) queries. However, existing approaches primarily focus on individual BI tasks such as NL2SQL and NL2VIS. The fragmentation of tasks across different data roles and tools lead to inefficiencies and potential errors due to the iterative and collaborative nature of BI. In this paper, we introduce DataLab, a unified BI platform that integrates a one-stop LLM-based agent framework with an augmented computational notebook interface. DataLab supports a wide range of BI tasks for different data roles by seamlessly combining LLM assistance with user customization within a single environment. To achieve this unification, we design a domain knowledge incorporation module tailored for enterprise-specific BI tasks, an inter-agent communication mechanism to facilitate information sharing across the BI workflow, and a cell-based context management strategy to enhance context utilization efficiency in BI notebooks. Extensive experiments demonstrate that DataLab achieves state-of-the-art performance on various BI tasks across popular research benchmarks. Moreover, DataLab maintains high effectiveness and efficiency on real-world datasets from Tencent, achieving up to a 58.58% increase in accuracy and a 61.65% reduction in token cost on enterprise-specific BI tasks.

[Arxiv](https://arxiv.org/abs/2412.02205)