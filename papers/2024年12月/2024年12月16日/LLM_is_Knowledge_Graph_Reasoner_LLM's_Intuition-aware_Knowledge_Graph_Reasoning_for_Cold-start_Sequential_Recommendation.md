# LLM 作为知识图谱推理器：基于直觉感知的知识图谱推理助力冷启动序列推荐

发布时间：2024年12月16日

`Agent

理由：这篇论文提出了一种名为LIKR的模型，该模型将大型语言模型（LLMs）视为推理器，通过强化学习训练推荐代理，整合LLM直觉和知识图谱（KG）嵌入等推荐策略。这种方法涉及到代理（Agent）的概念，即通过强化学习训练的推荐代理来执行推荐任务。因此，这篇论文更适合归类为Agent。` `推荐系统` `知识图谱`

> LLM is Knowledge Graph Reasoner: LLM's Intuition-aware Knowledge Graph Reasoning for Cold-start Sequential Recommendation

# 摘要

> # 摘要
知识图谱（KGs）以图结构表示实体间关系，是实现精准内容推荐的有力工具。然而，传统KG推荐方法存在两大挑战：时间信息利用不足和冷启动场景表现不佳。与此同时，大型语言模型（LLMs）作为从海量网络数据中学习的知识库，因其在推荐系统中的应用潜力而备受关注。尽管LLMs推荐方法能发挥其高推荐素养，但输入令牌限制使其难以处理整个推荐领域数据集，导致可扩展性问题。为此，我们提出了LLM直觉感知知识图谱推理模型（LIKR）。该模型将LLMs视为输出KG探索策略的推理器，通过强化学习训练推荐代理，整合LLM直觉和KG嵌入等推荐策略。LIKR通过提示工程融入时间意识，并从有限交互中生成用户偏好文本表示，从而提升冷启动场景的推荐性能。此外，LIKR利用KGs表示推荐领域数据集，并将LLM输出限制为KG探索策略，有效避免了可扩展性问题。真实数据集实验表明，LIKR在冷启动顺序推荐场景中优于现有最先进方法。

> Knowledge Graphs (KGs) represent relationships between entities in a graph structure and have been widely studied as promising tools for realizing recommendations that consider the accurate content information of items. However, traditional KG-based recommendation methods face fundamental challenges: insufficient consideration of temporal information and poor performance in cold-start scenarios. On the other hand, Large Language Models (LLMs) can be considered databases with a wealth of knowledge learned from the web data, and they have recently gained attention due to their potential application as recommendation systems. Although approaches that treat LLMs as recommendation systems can leverage LLMs' high recommendation literacy, their input token limitations make it impractical to consider the entire recommendation domain dataset and result in scalability issues. To address these challenges, we propose a LLM's Intuition-aware Knowledge graph Reasoning model (LIKR). Our main idea is to treat LLMs as reasoners that output intuitive exploration strategies for KGs. To integrate the knowledge of LLMs and KGs, we trained a recommendation agent through reinforcement learning using a reward function that integrates different recommendation strategies, including LLM's intuition and KG embeddings. By incorporating temporal awareness through prompt engineering and generating textual representations of user preferences from limited interactions, LIKR can improve recommendation performance in cold-start scenarios. Furthermore, LIKR can avoid scalability issues by using KGs to represent recommendation domain datasets and limiting the LLM's output to KG exploration strategies. Experiments on real-world datasets demonstrate that our model outperforms state-of-the-art recommendation methods in cold-start sequential recommendation scenarios.

[Arxiv](https://arxiv.org/abs/2412.12464)