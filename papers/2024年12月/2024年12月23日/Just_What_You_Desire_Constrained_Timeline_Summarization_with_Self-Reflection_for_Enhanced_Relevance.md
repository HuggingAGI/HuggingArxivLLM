# 正是你所期望的：通过自我反思实现约束时间线摘要，增强相关性

发布时间：2024年12月23日

`LLM应用` `时间线总结`

> Just What You Desire: Constrained Timeline Summarization with Self-Reflection for Enhanced Relevance

# 摘要

> 给定有关某个实体（比如公众人物或组织）的新闻报道，时间线总结（TLS）就是生成一条能概括该实体关键事件的时间线。然而，TLS 任务的界定太不清晰了，因为每个读者的兴趣点可能不同，所以不存在唯一理想或最优的时间线。在本文中，我们引入了一个全新的任务，叫做受限时间线总结（CTLS），在这个任务里生成的时间线中，所有事件都要符合某些约束条件。比如关于老虎伍兹法律纠纷的受限时间线，只有与他法律问题相关的事件才会被选入时间线。我们收集了一个新的经过人工验证的受限时间线数据集，涵盖 47 个实体，每个实体有 5 个约束。我们提出了一种运用大型语言模型（LLM）按照指定约束来总结新闻报道，并对其进行聚类以确定受限时间线中要包含的关键事件的方法。另外，我们在总结生成期间提出了一种新颖的自我反思方法，表明此方法成功提升了性能。

> Given news articles about an entity, such as a public figure or organization, timeline summarization (TLS) involves generating a timeline that summarizes the key events about the entity. However, the TLS task is too underspecified, since what is of interest to each reader may vary, and hence there is not a single ideal or optimal timeline. In this paper, we introduce a novel task, called Constrained Timeline Summarization (CTLS), where a timeline is generated in which all events in the timeline meet some constraint. An example of a constrained timeline concerns the legal battles of Tiger Woods, where only events related to his legal problems are selected to appear in the timeline. We collected a new human-verified dataset of constrained timelines involving 47 entities and 5 constraints per entity. We propose an approach that employs a large language model (LLM) to summarize news articles according to a specified constraint and cluster them to identify key events to include in a constrained timeline. In addition, we propose a novel self-reflection method during summary generation, demonstrating that this approach successfully leads to improved performance.

[Arxiv](https://arxiv.org/abs/2412.17408)