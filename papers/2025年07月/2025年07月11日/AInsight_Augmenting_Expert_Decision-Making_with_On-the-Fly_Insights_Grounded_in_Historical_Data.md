# AInsight：用历史数据驱动的即时洞察力，助力专家更明智地决策

发布时间：2025年07月11日

`RAG` `知识图谱`

> AInsight: Augmenting Expert Decision-Making with On-the-Fly Insights Grounded in Historical Data

# 摘要

> 在决策对话中，专家需要在交流过程中处理复杂的选项并做出即时决定。尽管通常存在大量历史数据，但这些场景的实时性质使得决策者无法查阅和利用相关信息。这引发了一个有趣的问题：如果专家能够通过从过去数据中获得的见解，在实时决策中利用相关的过去数据，会怎样？为了探索这一点，我们以医生与患者互动为例，实现了一个对话用户界面。我们的系统持续监听对话，识别患者的问题和医生建议的解决方案，并从嵌入的数据集中检索相关信息，通过基于检索的大型语言模型（LLM）代理构建的管道生成简洁的见解。我们通过将Health Canada的数据集嵌入向量数据库，并使用示例医生与患者对话进行模拟研究来评估该原型系统，结果显示了有效性但也存在挑战，为我们的下一步工作指明了方向。

> In decision-making conversations, experts must navigate complex choices and make on-the-spot decisions while engaged in conversation. Although extensive historical data often exists, the real-time nature of these scenarios makes it infeasible for decision-makers to review and leverage relevant information. This raises an interesting question: What if experts could utilize relevant past data in real-time decision-making through insights derived from past data? To explore this, we implemented a conversational user interface, taking doctor-patient interactions as an example use case. Our system continuously listens to the conversation, identifies patient problems and doctor-suggested solutions, and retrieves related data from an embedded dataset, generating concise insights using a pipeline built around a retrieval-based Large Language Model (LLM) agent. We evaluated the prototype by embedding Health Canada datasets into a vector database and conducting simulated studies using sample doctor-patient dialogues, showing effectiveness but also challenges, setting directions for the next steps of our work.

[Arxiv](https://arxiv.org/abs/2507.09100)