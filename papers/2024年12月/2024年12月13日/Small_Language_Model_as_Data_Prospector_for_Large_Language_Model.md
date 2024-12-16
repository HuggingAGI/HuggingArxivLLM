# 小型语言模型充当大型语言模型的数据探寻者

发布时间：2024年12月13日

`LLM应用` `数据筛选`

> Small Language Model as Data Prospector for Large Language Model

# 摘要

> 教学数据的质量直接影响着微调后的大型语言模型（LLMs）的性能。此前，\cite{li2023one}提出了	exttt{NUGGETS}，它能从大型数据集中识别并挑选出高质量数据，方法是找出那些作为一次性实例学习后能显著提升不同任务性能的单个教学示例。在本研究中，我们提出了	exttt{SuperNUGGETS}，这是	exttt{NUGGETS}的改进版，对效率和性能进行了优化。我们的	exttt{SuperNUGGETS}使用小型语言模型（SLM）而非大型语言模型（LLM）来筛选出优秀的一次性实例数据，并对预定义的测试集进行了优化。实验结果显示，与	exttt{NUGGETS}相比，	exttt{SuperNUGGETS}的性能仅下降 1 - 2%，但效率能提升 58 倍。相较于原始的	exttt{NUGGETS}，由于资源消耗大幅降低，我们的	exttt{SuperNUGGETS}具有更高的实用价值。

> The quality of instruction data directly affects the performance of fine-tuned Large Language Models (LLMs). Previously, \cite{li2023one} proposed \texttt{NUGGETS}, which identifies and selects high-quality quality data from a large dataset by identifying those individual instruction examples that can significantly improve the performance of different tasks after being learnt as one-shot instances. In this work, we propose \texttt{SuperNUGGETS}, an improved variant of \texttt{NUGGETS} optimised for efficiency and performance. Our \texttt{SuperNUGGETS} uses a small language model (SLM) instead of a large language model (LLM) to filter the data for outstanding one-shot instances and refines the predefined set of tests. The experimental results show that the performance of \texttt{SuperNUGGETS} only decreases by 1-2% compared to \texttt{NUGGETS}, but the efficiency can be increased by a factor of 58. Compared to the original \texttt{NUGGETS}, our \texttt{SuperNUGGETS} has a higher utility value due to the significantly lower resource consumption.

[Arxiv](https://arxiv.org/abs/2412.09990)