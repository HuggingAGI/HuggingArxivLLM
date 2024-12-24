# 一个基于大型语言模型的双视角隐喻检测框架

发布时间：2024年12月23日

`LLM应用` `隐喻检测`

> A Dual-Perspective Metaphor Detection Framework Using Large Language Models

# 摘要

> 隐喻检测是自然语言处理中的关键任务，旨在判定句子中的特定单词是否被隐喻性地运用。传统方法多依赖于监督学习模型，这些模型依据隐喻理论隐式编码语义关系。但此类方法的决策过程常缺乏透明度，影响了预测的可靠性。最新研究显示，LLMs（大型语言模型）在隐喻检测领域潜力巨大。不过，其推理能力受预定义知识图谱所限。为突破这些局限，我们提出了 DMD 这一新颖的双视角框架，它借助隐喻理论的隐式和显式应用来引导 LLMs 进行隐喻检测，并采用自我判断机制来验证上述引导方式的响应。和以往方法相比，我们的框架推理过程更透明，预测更可靠。实验结果证实了 DMD 的有效性，在广泛使用的数据集中展现出了顶尖的性能。

> Metaphor detection, a critical task in natural language processing, involves identifying whether a particular word in a sentence is used metaphorically. Traditional approaches often rely on supervised learning models that implicitly encode semantic relationships based on metaphor theories. However, these methods often suffer from a lack of transparency in their decision-making processes, which undermines the reliability of their predictions. Recent research indicates that LLMs (large language models) exhibit significant potential in metaphor detection. Nevertheless, their reasoning capabilities are constrained by predefined knowledge graphs. To overcome these limitations, we propose DMD, a novel dual-perspective framework that harnesses both implicit and explicit applications of metaphor theories to guide LLMs in metaphor detection and adopts a self-judgment mechanism to validate the responses from the aforementioned forms of guidance. In comparison to previous methods, our framework offers more transparent reasoning processes and delivers more reliable predictions. Experimental results prove the effectiveness of DMD, demonstrating state-of-the-art performance across widely-used datasets.

[Arxiv](https://arxiv.org/abs/2412.17332)