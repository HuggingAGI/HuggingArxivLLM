# 通过LLM驱动的实体关系图理解长视频

发布时间：2025年01月27日

`Agent

理由：这篇论文介绍了一个名为GraphVideoAgent的系统，该系统结合了基于图的对象跟踪和大型语言模型的能力，用于扩展视频内容的分析。该系统通过动态图结构来映射和监控视频序列中视觉实体间的关系演变，从而更细致地理解对象随时间的交互和变化。这种系统可以被视为一个智能代理（Agent），因为它能够自主地处理和分析视频内容，并根据上下文感知优化帧选择。因此，这篇论文应被分类为Agent。` `视频分析` `人工智能`

> Understanding Long Videos via LLM-Powered Entity Relation Graphs

# 摘要

> # 摘要
扩展视频内容的分析在人工智能领域面临独特挑战，尤其是在跨时间跟踪和理解视觉元素的复杂性方面。现有方法按顺序处理视频帧，难以保持对对象的一致跟踪，尤其是当对象暂时消失后重新出现时。这些方法的关键局限在于无法有效识别视频中的关键时刻，主要因为对时间关系的理解不足。为应对这些挑战，我们提出了GraphVideoAgent，这是一个结合了基于图的对象跟踪和大型语言模型能力的尖端系统。我们的框架采用动态图结构，映射并监控视频序列中视觉实体间的关系演变。这种创新方法能更细致地理解对象随时间的交互和变化，通过全面的上下文感知优化帧选择。在行业基准测试中，GraphVideoAgent表现出色。在EgoSchema数据集上，性能提升2.2，平均仅需分析8.2帧；在NExT-QA基准测试中，性能提升2.0，平均帧需求为8.1。这些结果证明了我们基于图的方法在提升长视频理解任务准确性和计算性能方面的显著优势。

> The analysis of extended video content poses unique challenges in artificial intelligence, particularly when dealing with the complexity of tracking and understanding visual elements across time. Current methodologies that process video frames sequentially struggle to maintain coherent tracking of objects, especially when these objects temporarily vanish and later reappear in the footage. A critical limitation of these approaches is their inability to effectively identify crucial moments in the video, largely due to their limited grasp of temporal relationships. To overcome these obstacles, we present GraphVideoAgent, a cutting-edge system that leverages the power of graph-based object tracking in conjunction with large language model capabilities. At its core, our framework employs a dynamic graph structure that maps and monitors the evolving relationships between visual entities throughout the video sequence. This innovative approach enables more nuanced understanding of how objects interact and transform over time, facilitating improved frame selection through comprehensive contextual awareness. Our approach demonstrates remarkable effectiveness when tested against industry benchmarks. In evaluations on the EgoSchema dataset, GraphVideoAgent achieved a 2.2 improvement over existing methods while requiring analysis of only 8.2 frames on average. Similarly, testing on the NExT-QA benchmark yielded a 2.0 performance increase with an average frame requirement of 8.1. These results underscore the efficiency of our graph-guided methodology in enhancing both accuracy and computational performance in long-form video understanding tasks.

[Arxiv](https://arxiv.org/abs/2501.15953)