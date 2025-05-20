# 有效且透明的 RAG：通过自适应奖励强化学习实现决策可追溯性

发布时间：2025年05月19日

`RAG` `知识密集型领域` `知识管理`

> Effective and Transparent RAG: Adaptive-Reward Reinforcement Learning for Decision Traceability

# 摘要

> 检索增强生成（RAG）在知识密集型领域为大型语言模型（LLMs）带来了显著提升。尽管RAG在多个领域取得了成功，但仍面临两大挑战：1）如何提升LLM利用检索信息进行推理和生成的能力？现有研究多聚焦于开发更强大的RAG检索器，但对生成器能力的提升仍待突破。2）如何提高模型的可解释性？大多数RAG方法忽略了对推理过程的可视化，导致缺乏透明性。

针对上述问题，我们提出了ARENA框架，一个通过强化学习（RL）训练的透明RAG生成框架。基于结构化生成和自适应奖励计算，ARENA能够识别关键证据，执行结构化推理，并生成带有可解释决策轨迹的回答。在Qwen2.5-7B-Instruct和Llama3.1-8B-Instruct上的实验表明，与现有基线相比，ARENA在多跳问答数据集上实现了10-30%的性能提升，与商用SOTA模型（如OpenAI-o1、DeepSeek-R1）相当。此外，ARENA具有良好的灵活性，可直接应用于新数据集而无需额外训练。我们的模型和代码已公开发布。

> Retrieval-Augmented Generation (RAG) has significantly improved the performance of large language models (LLMs) on knowledge-intensive domains. However, although RAG achieved successes across distinct domains, there are still some unsolved challenges: 1) Effectiveness. Existing research mainly focuses on developing more powerful RAG retrievers, but how to enhance the generator's (LLM's) ability to utilize the retrieved information for reasoning and generation? 2) Transparency. Most RAG methods ignore which retrieved content actually contributes to the reasoning process, resulting in a lack of interpretability and visibility. To address this, we propose ARENA (Adaptive-Rewarded Evidence Navigation Agent), a transparent RAG generator framework trained via reinforcement learning (RL) with our proposed rewards. Based on the structured generation and adaptive reward calculation, our RL-based training enables the model to identify key evidence, perform structured reasoning, and generate answers with interpretable decision traces. Applied to Qwen2.5-7B-Instruct and Llama3.1-8B-Instruct, abundant experiments with various RAG baselines demonstrate that our model achieves 10-30% improvements on all multi-hop QA datasets, which is comparable with the SOTA Commercially-developed LLMs (e.g., OpenAI-o1, DeepSeek-R1). Further analyses show that ARENA has strong flexibility to be adopted on new datasets without extra training. Our models and codes are publicly released.

[Arxiv](https://arxiv.org/abs/2505.13258)