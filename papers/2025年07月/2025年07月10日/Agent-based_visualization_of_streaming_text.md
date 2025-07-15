# # 基于智能体的实时流文本可视化

发布时间：2025年07月10日

`Agent` `可视化` `文本处理`

> Agent-based visualization of streaming text

# 摘要

> 我们提出了一种可视化基础设施，通过将数据元素映射到具有参数化行为的智能体，实现动态可视化效果。智能体根据位置变化、外观调整及相互作用呈现动态效果。其移动策略旨在最小化显示距离与理想距离矩阵之间的差异。当前应用聚焦于流式文本可视化，每个智能体代表一个关键单词，以圆圈形式呈现，圆圈大小反映单词频率。我们从单词共现关系中推导出理想距离矩阵，共现频率越高，距离越近。通过交集与圆圈面积的比率近似共现与频率的比例，实现文本上下文中共现关系的可视化。后端系统从新闻源、博客、Digg或Twitter等平台获取文章，并利用在线搜索API聚焦用户选定主题。最终可视化效果以集群形式呈现文本流中的主要主题，基于智能体的布局在数据动态变化时保持稳定。

> We present a visualization infrastructure that maps data elements to agents, which have behaviors parameterized by those elements. Dynamic visualizations emerge as the agents change position, alter appearance and respond to one other. Agents move to minimize the difference between displayed agent-to-agent distances, and an input matrix of ideal distances. Our current application is visualization of streaming text. Each agent represents a significant word, visualizing it by displaying the word itself, centered in a circle sized by the frequency of word occurrence. We derive the ideal distance matrix from word cooccurrence, mapping higher co-occurrence to lower distance. To depict co-occurrence in its textual context, the ratio of intersection to circle area approximates the ratio of word co-occurrence to frequency. A networked backend process gathers articles from news feeds, blogs, Digg or Twitter, exploiting online search APIs to focus on user-chosen topics. Resulting visuals reveal the primary topics in text streams as clusters, with agent-based layout moving without instability as data streams change dynamically.

[Arxiv](https://arxiv.org/abs/2507.08884)