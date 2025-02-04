# KBQA-o1: 智能体知识库问答与蒙特卡洛树搜索

发布时间：2025年01月31日

`Agent

理由：这篇论文提出了一种基于蒙特卡洛树搜索（MCTS）的新型智能体KBQA方法（KBQA-o1），该方法通过ReAct智能体逐步生成逻辑形式并探索知识库环境。论文的核心内容围绕智能体的设计和应用展开，因此应归类为Agent。` `知识库` `问答系统`

> KBQA-o1: Agentic Knowledge Base Question Answering with Monte Carlo Tree Search

# 摘要

> # 知识库问答（KBQA）旨在利用大规模结构化知识库（KB）回答自然语言问题。尽管大型语言模型（LLMs）取得了显著进展，KBQA仍面临知识库意识不足、效果与效率失衡以及对标注数据依赖过高等挑战。为此，我们提出了KBQA-o1，一种基于蒙特卡洛树搜索（MCTS）的新型智能体KBQA方法。该方法通过ReAct智能体逐步生成逻辑形式并探索知识库环境，同时利用MCTS这一启发式搜索方法，平衡智能体探索的性能与搜索空间。通过启发式探索，KBQA-o1生成了高质量的标注数据，并通过增量微调进一步提升性能。实验结果显示，KBQA-o1在有限标注数据下表现优异，将Llama-3.1-8B模型的GrailQA F1性能提升至78.5%，远超之前使用GPT-3.5-turbo的最先进方法的48.5%。

> Knowledge Base Question Answering (KBQA) aims to answer natural language questions with a large-scale structured knowledge base (KB). Despite advancements with large language models (LLMs), KBQA still faces challenges in weak KB awareness, imbalance between effectiveness and efficiency, and high reliance on annotated data. To address these challenges, we propose KBQA-o1, a novel agentic KBQA method with Monte Carlo Tree Search (MCTS). It introduces a ReAct-based agent process for stepwise logical form generation with KB environment exploration. Moreover, it employs MCTS, a heuristic search method driven by policy and reward models, to balance agentic exploration's performance and search space. With heuristic exploration, KBQA-o1 generates high-quality annotations for further improvement by incremental fine-tuning. Experimental results show that KBQA-o1 outperforms previous low-resource KBQA methods with limited annotated data, boosting Llama-3.1-8B model's GrailQA F1 performance to 78.5% compared to 48.5% of the previous sota method with GPT-3.5-turbo.

[Arxiv](https://arxiv.org/abs/2501.18922)