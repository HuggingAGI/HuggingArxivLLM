# # 自然语言交互中的动态联盟结构检测

发布时间：2025年02月22日

`LLM应用` `博弈论`

> Dynamic Coalition Structure Detection in Natural Language-based Interactions

# 摘要

> 在战略型多智能体交互中，理解动态联盟结构的识别对于解析自利型智能体如何协作以影响结果至关重要。然而，自然语言交互带来的独特挑战，如意图模糊和主观视角建模困难，使得联盟检测更具难度。我们提出了一种结合大型语言模型与博弈论的新方法，用于预测《外交》游戏中基于自然语言的动态联盟形成。该方法分为两步：首先，通过结合解析过滤函数与微调语言模型提取智能体间的协议集；其次，基于超博弈理论定义新指标评估协议价值。实验表明，该方法能有效识别潜在联盟结构，为多智能体环境下的联盟分析提供了重要见解。

> In strategic multi-agent sequential interactions, detecting dynamic coalition structures is crucial for understanding how self-interested agents coordinate to influence outcomes. However, natural-language-based interactions introduce unique challenges to coalition detection due to ambiguity over intents and difficulty in modeling players' subjective perspectives. We propose a new method that leverages recent advancements in large language models and game theory to predict dynamic multilateral coalition formation in Diplomacy, a strategic multi-agent game where agents negotiate coalitions using natural language. The method consists of two stages. The first stage extracts the set of agreements discussed by two agents in their private dialogue, by combining a parsing-based filtering function with a fine-tuned language model trained to predict player intents. In the second stage, we define a new metric using the concept of subjective rationalizability from hypergame theory to evaluate the expected value of an agreement for each player. We then compute this metric for each agreement identified in the first stage by assessing the strategic value of the agreement for both players and taking into account the subjective belief of one player that the second player would honor the agreement. We demonstrate that our method effectively detects potential coalition structures in online Diplomacy gameplay by assigning high values to agreements likely to be honored and low values to those likely to be violated. The proposed method provides foundational insights into coalition formation in multi-agent environments with language-based negotiation and offers key directions for future research on the analysis of complex natural language-based interactions between agents.

[Arxiv](https://arxiv.org/abs/2502.16339)