# # 迈向公平排名：利用大型语言模型检测与衡量性别偏见

发布时间：2025年06月27日

`LLM应用` `信息检索` `性别偏见`

> Towards Fair Rankings: Leveraging LLMs for Gender Bias Detection and Measurement

# 摘要

> 自然语言处理（NLP）和信息检索（IR）系统中的社会偏见问题持续存在，这凸显了开发 robust 方法以识别和评估此类偏见的重要性。本文旨在通过利用大型语言模型（LLMs）来检测和测量段落排序中的性别偏见，从而解决这一问题。现有的性别公平度量依赖于基于词汇和频率的措施，导致了各种限制，例如遗漏微妙的性别差异。基于我们基于LLM的性别偏见检测方法，我们引入了一种新的性别公平度量，名为类加权曝光（Class-wise Weighted Exposure，CWEx），旨在解决现有局限性。为了衡量我们提出度量的有效性，并研究LLMs在检测性别偏见方面的有效性，我们标注了MS MARCO段落排序集合的一个子集，并发布了名为MSMGenderBias的新性别偏见集合，以促进未来在该领域的研究。我们在各种排序模型上的广泛实验结果表明，与之前的度量相比，我们的提出的度量提供了更详细的公平性评估，与人工标注的标签具有更好的一致性（使用Cohen's Kappa协议测量，Grep-BiasIR为58.77%，MSMGenderBias为18.51%），能够有效区分排序中的性别偏见。通过整合基于LLM的偏见检测、改进的公平度量以及对现有数据集的性别偏见标注，这项工作为分析和缓解IR系统中的偏见提供了一个更 robust 的框架。

> The presence of social biases in Natural Language Processing (NLP) and Information Retrieval (IR) systems is an ongoing challenge, which underlines the importance of developing robust approaches to identifying and evaluating such biases. In this paper, we aim to address this issue by leveraging Large Language Models (LLMs) to detect and measure gender bias in passage ranking. Existing gender fairness metrics rely on lexical- and frequency-based measures, leading to various limitations, e.g., missing subtle gender disparities. Building on our LLM-based gender bias detection method, we introduce a novel gender fairness metric, named Class-wise Weighted Exposure (CWEx), aiming to address existing limitations. To measure the effectiveness of our proposed metric and study LLMs' effectiveness in detecting gender bias, we annotate a subset of the MS MARCO Passage Ranking collection and release our new gender bias collection, called MSMGenderBias, to foster future research in this area. Our extensive experimental results on various ranking models show that our proposed metric offers a more detailed evaluation of fairness compared to previous metrics, with improved alignment to human labels (58.77% for Grep-BiasIR, and 18.51% for MSMGenderBias, measured using Cohen's Kappa agreement), effectively distinguishing gender bias in ranking. By integrating LLM-driven bias detection, an improved fairness metric, and gender bias annotations for an established dataset, this work provides a more robust framework for analyzing and mitigating bias in IR systems.

[Arxiv](https://arxiv.org/abs/2506.22372)