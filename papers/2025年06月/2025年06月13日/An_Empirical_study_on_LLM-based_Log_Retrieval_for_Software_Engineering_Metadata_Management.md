# 基于大型语言模型的日志检索在软件工程元数据管理中的实证研究

发布时间：2025年06月13日

`LLM应用

分类理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来支持自动驾驶系统中的日志数据处理和场景搜索。具体来说，它提出了一种方法，将信号日志数据与试驾视频记录相结合，实现基于自然语言的场景搜索，并通过API提供高效查询和可视化结果。这种方法属于LLM的应用，因为它展示了如何将LLM用于解决实际问题（即自动驾驶系统中的日志数据分析）。` `自动驾驶` `数据管理`

> An Empirical study on LLM-based Log Retrieval for Software Engineering Metadata Management

# 摘要

> 开发自动驾驶系统 (ADSs) 需要生成和存储来自试驾的大量日志数据，这对于验证、研究和模拟至关重要。然而，这些高频日志在不同时间段记录的数据，使得开发者难以定位特定的驾驶场景。这种困难源于广泛代表各种车辆部件和驾驶条件的信号，以及部分开发者对这些信号的详细含义不熟悉。传统的基于 SQL 的查询方式加剧了这一挑战，因为它需要领域专业知识和数据库知识，通常会导致难以验证准确性的结果。
    本文介绍了一种由大型语言模型 (LLM) 支持的方法，将信号日志数据与试驾的视频记录相结合，实现基于自然语言的场景搜索，同时减少了对专业知识的需求。通过利用场景距离图和相对差距指标，它提供了可量化的指标来评估查询结果的可靠性。该方法作为 API 实现，用于高效查询数据库并检索相关记录，并配以视频帧进行直观可视化。在开放的工业数据集上的评估表明，场景检索的效率和可靠性得到了提升，摆脱了对单一数据源和传统 SQL 的依赖。

> Developing autonomous driving systems (ADSs) involves generating and storing extensive log data from test drives, which is essential for verification, research, and simulation. However, these high-frequency logs, recorded over varying durations, pose challenges for developers attempting to locate specific driving scenarios. This difficulty arises due to the wide range of signals representing various vehicle components and driving conditions, as well as unfamiliarity of some developers' with the detailed meaning of these signals. Traditional SQL-based querying exacerbates this challenge by demanding both domain expertise and database knowledge, often yielding results that are difficult to verify for accuracy.
  This paper introduces a Large Language Model (LLM)-supported approach that combines signal log data with video recordings from test drives, enabling natural language based scenario searches while reducing the need for specialized knowledge. By leveraging scenario distance graphs and relative gap indicators, it provides quantifiable metrics to evaluate the reliability of query results. The method is implemented as an API for efficient database querying and retrieval of relevant records, paired with video frames for intuitive visualization. Evaluation on an open industrial dataset demonstrates improved efficiency and reliability in scenario retrieval, eliminating dependency on a single data source and conventional SQL.

[Arxiv](https://arxiv.org/abs/2506.11659)