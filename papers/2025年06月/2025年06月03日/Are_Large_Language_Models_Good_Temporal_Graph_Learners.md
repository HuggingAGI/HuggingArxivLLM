# 大型语言模型擅长时序图学习吗？

发布时间：2025年06月03日

`LLM应用` `网络科学` `时间图学习`

> Are Large Language Models Good Temporal Graph Learners?

# 摘要

> 大型语言模型 (LLMs) 近年来在自然语言处理及多个应用领域取得了显著突破。尽管已有大量研究探讨了 LLMs 的图推理能力，包括其在图结构上的预测应用，但将其应用于动态图（即现实世界中不断演进的网络）仍是一个未被充分探索的领域。近期研究主要集中在由随机图模型生成的合成时间图上，而将 LLMs 应用于现实世界的时间图仍是一个开放性问题。为填补这一研究空白，我们提出了 Temporal Graph Talker (TGTalker)——一个专为 LLMs 设计的全新时间图学习框架。TGTalker 基于时间图中的近期偏见，提取关键结构信息并将其转化为自然语言供 LLMs 处理，同时借助时间邻居提供额外预测信息。实验结果显示，TGTalker 在链路预测能力上可与现有时间图神经网络 (TGNN) 模型相媲美。在五个真实世界网络测试中，TGTalker 不仅与当前最优的时间图方法表现相当，更持续超越 TGN 和 HTGN 等流行模型。此外，TGTalker 能为每个预测结果生成文本解释，从而在时间图预测的可解释性方面开创了全新研究方向。项目代码已开源，访问地址为 https://github.com/shenyangHuang/TGTalker。

> Large Language Models (LLMs) have recently driven significant advancements in Natural Language Processing and various other applications. While a broad range of literature has explored the graph-reasoning capabilities of LLMs, including their use of predictors on graphs, the application of LLMs to dynamic graphs -- real world evolving networks -- remains relatively unexplored. Recent work studies synthetic temporal graphs generated by random graph models, but applying LLMs to real-world temporal graphs remains an open question. To address this gap, we introduce Temporal Graph Talker (TGTalker), a novel temporal graph learning framework designed for LLMs. TGTalker utilizes the recency bias in temporal graphs to extract relevant structural information, converted to natural language for LLMs, while leveraging temporal neighbors as additional information for prediction. TGTalker demonstrates competitive link prediction capabilities compared to existing Temporal Graph Neural Network (TGNN) models. Across five real-world networks, TGTalker performs competitively with state-of-the-art temporal graph methods while consistently outperforming popular models such as TGN and HTGN. Furthermore, TGTalker generates textual explanations for each prediction, thus opening up exciting new directions in explainability and interpretability for temporal link prediction. The code is publicly available at https://github.com/shenyangHuang/TGTalker.

[Arxiv](https://arxiv.org/abs/2506.05393)