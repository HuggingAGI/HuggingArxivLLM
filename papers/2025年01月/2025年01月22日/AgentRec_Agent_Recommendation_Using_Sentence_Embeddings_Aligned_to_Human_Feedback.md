# AgentRec: 基于人类反馈对齐的句子嵌入的智能体推荐

发布时间：2025年01月22日

`Agent

理由：这篇论文主要讨论的是多智能体系统中如何选择最适合执行特定任务的智能体，并提出了一种基于 Sentence-BERT 编码器模型的新架构来实现这一目标。论文的核心内容围绕智能体的推荐和选择，属于多智能体系统的研究和应用，因此应归类为Agent。` `多智能体系统`

> AgentRec: Agent Recommendation Using Sentence Embeddings Aligned to Human Feedback

# 摘要

> 多智能体系统需要确定哪个智能体最适合执行特定任务。我们提出了一种基于 Sentence-BERT (SBERT) 编码器模型的新架构，用于推荐在给定自然语言提示时，多个 LLM 智能体中应执行任务的智能体。在测试数据上，我们的模型实现了 92.2% 的 top-1 准确率，每次分类耗时不到 300 毫秒。与传统分类方法相比，该架构计算成本低，适应性强，可解释性高，并能通过强化学习使用任意指标进行控制。通过将自然语言提示编码为句子嵌入，模型捕捉到与智能体推荐相关的语义信息。通过微调最小化同一智能体的句子嵌入距离，并通过人类反馈的强化学习对齐人类价值观，模型能够基于嵌入的余弦相似度对自然语言提示进行分类。我们生成了一个用于智能体推荐的合成数据集，并将 AgentRec 推荐系统的代码开源，地址为 https://github.com/joshprk/agentrec。

> Multi-agent systems must decide which agent is the most appropriate for a given task. We propose a novel architecture for recommending which LLM agent out of many should perform a task given a natural language prompt by extending the Sentence-BERT (SBERT) encoder model. On test data, we are able to achieve a top-1 accuracy of 92.2% with each classification taking less than 300 milliseconds. In contrast to traditional classification methods, our architecture is computationally cheap, adaptive to new classes, interpretable, and controllable with arbitrary metrics through reinforcement learning. By encoding natural language prompts into sentence embeddings, our model captures the semantic content relevant to recommending an agent. The distance between sentence embeddings that belong to the same agent is then minimized through fine-tuning and aligned to human values through reinforcement learning from human feedback. This allows the classification of natural language prompts based on their nearest neighbors by measuring the cosine similarity between embeddings. This work is made possible through the generation of a synthetic dataset for agent recommendation, which we have open-sourced to the public along with the code for AgentRec recommendation system at https://github.com/joshprk/agentrec.

[Arxiv](https://arxiv.org/abs/2501.13333)