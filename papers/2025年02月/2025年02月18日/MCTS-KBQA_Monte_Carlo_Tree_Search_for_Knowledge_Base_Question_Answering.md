# MCTS-KBQA：蒙特卡洛树搜索应用于知识库问答

发布时间：2025年02月18日

`LLM应用` `问答系统`

> MCTS-KBQA: Monte Carlo Tree Search for Knowledge Base Question Answering

# 摘要

> 本研究旨在探索如何通过蒙特卡洛树搜索（MCTS）提升大型语言模型（LLMs）在知识库问答（KBQA）任务中的推理能力。基于语义解析的KBQA方法因其需要从知识库中提取信息并生成逻辑形式，对标注数据和推理能力的要求极高，因而极具挑战性。尽管近年来利用LLMs作为代理的方法展现出巨大潜力，但其线性决策过程的固有局限性限制了进一步提升。为此，我们提出了一种基于MCTS的框架，通过树搜索方法显著增强LLMs的推理能力。我们设计了一个分步奖励机制，仅需直接提示开源指令LLMs，无需额外微调。实验结果表明，相较于传统线性决策方法，我们的方法在低资源场景下表现尤为突出。此外，我们通过远程监督对现有问题-SPARQL数据集的中间推理过程进行了标注，为KBQA社区贡献了新的数据资源。在扩展数据集上的实验结果进一步证实，我们的方法在使用显著更少训练数据的情况下，性能已可与全监督模型相媲美。

> This study explores how to enhance the reasoning capabilities of large language models (LLMs) in knowledge base question answering (KBQA) by leveraging Monte Carlo Tree Search (MCTS). Semantic parsing-based KBQA methods are particularly challenging as these approaches require locating elements from knowledge bases and generating logical forms, demanding not only extensive annotated data but also strong reasoning capabilities. Although recent approaches leveraging LLMs as agents have demonstrated considerable potential, these studies are inherently constrained by their linear decision-making processes. To address this limitation, we propose a MCTS-based framework that enhances LLMs' reasoning capabilities through tree search methodology. We design a carefully designed step-wise reward mechanism that requires only direct prompting of open-source instruction LLMs without additional fine-tuning. Experimental results demonstrate that our approach significantly outperforms linear decision-making methods, particularly in low-resource scenarios. Additionally, we contribute new data resources to the KBQA community by annotating intermediate reasoning processes for existing question-SPARQL datasets using distant supervision. Experimental results on the extended dataset demonstrate that our method achieves comparable performance to fully supervised models while using significantly less training data.

[Arxiv](https://arxiv.org/abs/2502.13428)