# 从注意力机制视角探索 LLM 如何处理图结构数据

发布时间：2025年05月04日

`LLM理论`

> Attention Mechanisms Perspective: Exploring LLM Processing of Graph-Structured Data

# 摘要

> 注意力机制是大型语言模型 (LLMs) 取得成功的关键，推动了多个领域的显著进步。然而，对于需要强调拓扑连接的图结构数据，它们的表现却不如固定链接上的消息传递机制，例如图神经网络 (GNNs) 所采用的机制。这引出了一个问题：‘在自然语言环境下，注意力机制是否无法处理图结构数据？’基于这些观察，我们从注意力机制的视角出发，开展了一项实证研究，旨在探索大型语言模型如何处理图结构数据，并深入了解它们在图结构上的注意力行为。我们发现了一些关于大型语言模型如何将注意力应用于图结构数据的独特现象，并对这些发现进行了分析，以期改进大型语言模型对这类数据的建模能力。我们的主要研究发现包括：1) 尽管大型语言模型能够识别图数据并捕捉文本节点间的相互作用，但由于其固有的架构限制，它们难以有效建模图结构中节点间的相互关系。2) 大型语言模型在图节点上的注意力分布与理想的结构模式不一致，表明其未能适应图拓扑的细微差别。3) 无论是全连接注意力，还是固定连接，都没有达到最优效果；每种方法在其应用场景中都有特定的局限性。相比之下，中间状态的注意力窗口能够提升大型语言模型的训练表现，并在推理过程中无缝过渡到全连接窗口。源代码：\href{https://github.com/millioniron/LLM_exploration}{LLM4Exploration}

> Attention mechanisms are critical to the success of large language models (LLMs), driving significant advancements in multiple fields. However, for graph-structured data, which requires emphasis on topological connections, they fall short compared to message-passing mechanisms on fixed links, such as those employed by Graph Neural Networks (GNNs). This raises a question: ``Does attention fail for graphs in natural language settings?'' Motivated by these observations, we embarked on an empirical study from the perspective of attention mechanisms to explore how LLMs process graph-structured data. The goal is to gain deeper insights into the attention behavior of LLMs over graph structures. We uncovered unique phenomena regarding how LLMs apply attention to graph-structured data and analyzed these findings to improve the modeling of such data by LLMs. The primary findings of our research are: 1) While LLMs can recognize graph data and capture text-node interactions, they struggle to model inter-node relationships within graph structures due to inherent architectural constraints. 2) The attention distribution of LLMs across graph nodes does not align with ideal structural patterns, indicating a failure to adapt to graph topology nuances. 3) Neither fully connected attention nor fixed connectivity is optimal; each has specific limitations in its application scenarios. Instead, intermediate-state attention windows improve LLM training performance and seamlessly transition to fully connected windows during inference. Source code: \href{https://github.com/millioniron/LLM_exploration}{LLM4Exploration}

[Arxiv](https://arxiv.org/abs/2505.02130)