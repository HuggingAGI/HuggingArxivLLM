# RAG-RL：强化学习与课程学习助力检索增强生成能力提升

发布时间：2025年03月16日

`RAG` `问答系统`

> RAG-RL: Advancing Retrieval-Augmented Generation via RL and Curriculum Learning

# 摘要

> 近期研究揭示了检索模型在检索有用上下文方面的挑战，以及生成模型在RAG设置中有效利用这些上下文的局限性。为解决这些问题，我们推出了首个专为RAG设计的推理语言模型——RAG-RL。RAG-RL证明，更强大的生成模型不仅能在更大检索信息集中精准识别相关上下文，从而减轻检索器负担，还能更高效地利用这些上下文。此外，我们在强化学习后训练过程中发现，课程设计是提升模型性能的有力方法。我们在两个开放领域问答数据集上验证了这一方法，取得了超越现有最优模型的卓越效果。同时，我们对多种课程学习策略进行了深入分析，揭示了它们对模型性能的深远影响。

> Recent research highlights the challenges retrieval models face in retrieving useful contexts and the limitations of generation models in effectively utilizing those contexts in retrieval-augmented generation (RAG) settings. To address these challenges, we introduce RAG-RL, the first reasoning language model (RLM) specifically trained for RAG. RAG-RL demonstrates that stronger answer generation models can identify relevant contexts within larger sets of retrieved information -- thereby alleviating the burden on retrievers -- while also being able to utilize those contexts more effectively. Moreover, we show that curriculum design in the reinforcement learning (RL) post-training process is a powerful approach to enhancing model performance. We benchmark our method on two open-domain question-answering datasets and achieve state-of-the-art results, surpassing previous SOTA generative reader models. In addition, we offers empirical insights into various curriculum learning strategies, providing a deeper understanding of their impact on model performance.

[Arxiv](https://arxiv.org/abs/2503.12759)