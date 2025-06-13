# 大型语言模型检测生命威胁性文本

发布时间：2025年06月12日

`LLM应用` `心理健康`

> Large Language Models for Detection of Life-Threatening Texts

# 摘要

> 检测致命语言对于保护处于困境中的个体、促进心理健康与福祉以及预防潜在伤害和生命损失至关重要。本文提出了一种利用大型语言模型（LLMs）有效识别致命文本的方法，并将其与传统的袋装词、词嵌入、主题建模和双向编码器表示从变换器等方法进行了比较。我们使用Gemma、Mistral和Llama-2三种开源LLMs的不同数据集进行了微调，这些数据集分别构建了类别平衡、不平衡和极端不平衡的场景。实验结果表明，LLMs在传统方法面前表现出色。更具体地说，Mistral和Llama-2模型在平衡和不平衡数据场景中表现最佳，而Gemma则稍逊一筹。我们采用了上采样技术来处理不平衡的数据场景，并证明了虽然此方法对传统方法有益，但对LLMs的影响不大。本研究展示了LLMs在现实世界中检测致命语言问题的巨大潜力。

> Detecting life-threatening language is essential for safeguarding individuals in distress, promoting mental health and well-being, and preventing potential harm and loss of life. This paper presents an effective approach to identifying life-threatening texts using large language models (LLMs) and compares them with traditional methods such as bag of words, word embedding, topic modeling, and Bidirectional Encoder Representations from Transformers. We fine-tune three open-source LLMs including Gemma, Mistral, and Llama-2 using their 7B parameter variants on different datasets, which are constructed with class balance, imbalance, and extreme imbalance scenarios. Experimental results demonstrate a strong performance of LLMs against traditional methods. More specifically, Mistral and Llama-2 models are top performers in both balanced and imbalanced data scenarios while Gemma is slightly behind. We employ the upsampling technique to deal with the imbalanced data scenarios and demonstrate that while this method benefits traditional approaches, it does not have as much impact on LLMs. This study demonstrates a great potential of LLMs for real-world life-threatening language detection problems.

[Arxiv](https://arxiv.org/abs/2506.10687)