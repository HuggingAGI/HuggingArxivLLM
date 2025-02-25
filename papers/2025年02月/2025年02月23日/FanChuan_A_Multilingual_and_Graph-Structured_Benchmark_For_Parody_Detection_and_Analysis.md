# # FanChuan：一个多语言图结构基准数据集，用于讽刺检测与分析

发布时间：2025年02月23日

`LLM应用

摘要中提到的研究主要集中在利用大型语言模型（LLMs）来处理恶搞识别及其相关的情感分析任务，属于将LLMs应用于具体问题的范畴。因此，正确的分类是LLM应用。` `社交媒体`

> FanChuan: A Multilingual and Graph-Structured Benchmark For Parody Detection and Analysis

# 摘要

> 恶搞作为一种新兴的社交媒体现象，个体通过模仿与自身角色或立场相反的方式进行娱乐、挑衅或引发争议。尽管恶搞的识别和分析通常依赖于上下文，具有一定的挑战性，但它在理解文化价值观、促进亚文化以及增强自我表达方面发挥着关键作用。然而，恶搞研究受到可用数据有限以及现有数据集多样性不足的限制。为了填补这一空白，我们从英文和中文语料库中构建了7个恶搞数据集，总共包含14,755个标注用户和21,210条标注评论。为了提供更丰富的上下文信息，我们还收集了回复并构建了用户交互图，弥补了现有数据集的不足。利用这些数据集，我们在三个关键任务上测试了传统方法和大型语言模型（LLMs）：（1）恶搞识别，（2）结合恶搞的评论情感分析，（3）结合恶搞的用户情感分析。我们发现，恶搞相关的任务对所有模型来说仍然具有挑战性，而上下文信息起到了关键作用。有趣的是，在某些情况下，传统句子嵌入方法结合简单的分类器可以优于先进的LLMs（如DeepSeek-R1和GPT-o3），这表明恶搞对LLMs来说是一个重大挑战。

> Parody is an emerging phenomenon on social media, where individuals imitate a role or position opposite to their own, often for humor, provocation, or controversy. Detecting and analyzing parody can be challenging and is often reliant on context, yet it plays a crucial role in understanding cultural values, promoting subcultures, and enhancing self-expression. However, the study of parody is hindered by limited available data and deficient diversity in current datasets. To bridge this gap, we built seven parody datasets from both English and Chinese corpora, with 14,755 annotated users and 21,210 annotated comments in total. To provide sufficient context information, we also collect replies and construct user-interaction graphs to provide richer contextual information, which is lacking in existing datasets. With these datasets, we test traditional methods and Large Language Models (LLMs) on three key tasks: (1) parody detection, (2) comment sentiment analysis with parody, and (3) user sentiment analysis with parody. Our extensive experiments reveal that parody-related tasks still remain challenging for all models, and contextual information plays a critical role. Interestingly, we find that, in certain scenarios, traditional sentence embedding methods combined with simple classifiers can outperform advanced LLMs, i.e. DeepSeek-R1 and GPT-o3, highlighting parody as a significant challenge for LLMs.

[Arxiv](https://arxiv.org/abs/2502.16503)