# 适用于大型语言模型进行图推理的图线性化手段

发布时间：2024年10月25日

`LLM应用` `图机器学习` `多模态处理`

> Graph Linearization Methods for Reasoning on Graphs with Large Language Models

# 摘要

> 大型语言模型已进化到能处理除文本外的多种模态，像图像和音频，这促使我们去探索如何有效利用它们来完成图机器学习任务。所以，关键问题在于怎样把图转化为标记的线性序列，我们称此过程为图线性化，从而让大型语言模型能自然地处理图。我们觉得，图应当被有意义地线性化，以体现自然语言文本的某些特性，比如局部依赖和全局对齐，以便让在数万亿文本标记上训练的当代大型语言模型更轻松地理解图。为达此目的，我们基于图的中心性、简并性和节点重标记方案开发了若干图线性化方法。接着，我们探究了它们在图推理任务中对大型语言模型性能的影响。在合成图上的实验结果表明，相较于随机线性化基线，我们的方法是有效的。我们的工作引入了适用于大型语言模型的新型图表示，有助于将图机器学习与使用统一转换器模型的多模态处理趋势潜在地融合起来。

> Large language models have evolved to process multiple modalities beyond text, such as images and audio, which motivates us to explore how to effectively leverage them for graph machine learning tasks. The key question, therefore, is how to transform graphs into linear sequences of tokens, a process we term graph linearization, so that LLMs can handle graphs naturally. We consider that graphs should be linearized meaningfully to reflect certain properties of natural language text, such as local dependency and global alignment, in order to ease contemporary LLMs, trained on trillions of textual tokens, better understand graphs. To achieve this, we developed several graph linearization methods based on graph centrality, degeneracy, and node relabeling schemes. We then investigated their effect on LLM performance in graph reasoning tasks. Experimental results on synthetic graphs demonstrate the effectiveness of our methods compared to random linearization baselines. Our work introduces novel graph representations suitable for LLMs, contributing to the potential integration of graph machine learning with the trend of multi-modal processing using a unified transformer model.

[Arxiv](https://arxiv.org/abs/2410.19494)