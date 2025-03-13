# 基于众包同质关系的大型语言模型图标注

发布时间：2025年03月12日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于图标注任务中，通过结合众包标注和LLMs的能力来优化标注过程。具体来说，CSA-LLM方法利用了图数据的结构上下文和homophily ties，从而提升标注的准确性，并最终提高图神经网络的性能。这属于将LLMs应用于具体任务的范畴，因此归类为LLM应用。` `图计算` `数据处理`

> Crowdsourced Homophily Ties Based Graph Annotation Via Large Language Model

# 摘要

> 图标注的准确性通常需要大量标注数据，而这些数据的获取往往具有挑战性且耗费资源。本文提出了一种名为 CSA-LLM 的创新方法，该方法结合了众包标注的优势与大型语言模型（LLMs）的能力，旨在优化图标注过程。CSA-LLM 通过整合 1 跳和 2 跳邻居的信息，充分利用图数据的结构上下文。通过强调 homophily ties（图中表示相似性的关键连接），CSA-LLM 显著提升了标注的准确性。实验结果表明，该方法通过提供更精确和可靠的标注，显著提升了图神经网络（GNNs）的性能。

> Accurate graph annotation typically requires substantial labeled data, which is often challenging and resource-intensive to obtain. In this paper, we present Crowdsourced Homophily Ties Based Graph Annotation via Large Language Model (CSA-LLM), a novel approach that combines the strengths of crowdsourced annotations with the capabilities of large language models (LLMs) to enhance the graph annotation process. CSA-LLM harnesses the structural context of graph data by integrating information from 1-hop and 2-hop neighbors. By emphasizing homophily ties - key connections that signify similarity within the graph - CSA-LLM significantly improves the accuracy of annotations. Experimental results demonstrate that this method enhances the performance of Graph Neural Networks (GNNs) by delivering more precise and reliable annotations.

[Arxiv](https://arxiv.org/abs/2503.09281)