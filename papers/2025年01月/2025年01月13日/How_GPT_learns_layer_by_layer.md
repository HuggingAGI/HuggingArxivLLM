# GPT 的逐层学习机制

发布时间：2025年01月13日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在构建内部世界模型方面的能力，特别是通过研究OthelloGPT模型来理解LLMs如何学习和表示复杂任务中的信息。论文的重点在于分析LLMs的内部表示机制，以及如何通过稀疏自编码器（SAEs）和线性探针来解释这些表示。这些研究内容属于对LLMs内部工作机制的理论性探讨，因此归类为“LLM理论”。` `人工智能`

> How GPT learns layer by layer

# 摘要

> # 摘要
大型语言模型（LLMs）在语言处理、策略游戏和推理等任务上表现出色，但在构建智能体自适应决策所需的可泛化内部表示方面却力不从心。智能体要在复杂环境中游刃有余，必须构建可靠的世界模型。尽管LLMs在特定基准测试中表现优异，但其泛化能力不足，导致表示脆弱，限制了实际应用效果。理解LLMs如何构建内部世界模型，是开发具备跨任务一致性和自适应行为智能体的关键。我们以OthelloGPT为例，这是一个基于GPT的模型，经过Othello游戏训练，作为研究表示学习的受控测试平台。尽管仅通过随机有效移动的下一个标记预测进行训练，OthelloGPT在理解棋盘状态和游戏玩法方面展现出有意义的分层进展：早期层捕捉静态属性（如棋盘边缘），而更深层则反映动态的棋子变化。为解释这些表示，我们比较了稀疏自编码器（SAEs）与线性探针，发现SAEs能提供更稳健、解耦的组合特征洞察，而线性探针主要检测对分类有用的特征。我们利用SAEs解码了与棋子颜色和棋子稳定性相关的特征，后者是此前未研究的特征，反映了复杂的游戏概念，如棋盘控制和长期规划。通过SAEs和线性探针，我们研究了线性探针准确性和棋子颜色的进展，比较了它们在捕捉模型学习内容方面的有效性。尽管我们从一个较小的语言模型OthelloGPT起步，但这项研究为更广泛地理解GPT模型、变压器和LLMs学习的内部表示奠定了基础。我们的代码公开可用：https://github.com/ALT-JS/OthelloSAE。

> Large Language Models (LLMs) excel at tasks like language processing, strategy games, and reasoning but struggle to build generalizable internal representations essential for adaptive decision-making in agents. For agents to effectively navigate complex environments, they must construct reliable world models. While LLMs perform well on specific benchmarks, they often fail to generalize, leading to brittle representations that limit their real-world effectiveness. Understanding how LLMs build internal world models is key to developing agents capable of consistent, adaptive behavior across tasks. We analyze OthelloGPT, a GPT-based model trained on Othello gameplay, as a controlled testbed for studying representation learning. Despite being trained solely on next-token prediction with random valid moves, OthelloGPT shows meaningful layer-wise progression in understanding board state and gameplay. Early layers capture static attributes like board edges, while deeper layers reflect dynamic tile changes. To interpret these representations, we compare Sparse Autoencoders (SAEs) with linear probes, finding that SAEs offer more robust, disentangled insights into compositional features, whereas linear probes mainly detect features useful for classification. We use SAEs to decode features related to tile color and tile stability, a previously unexamined feature that reflects complex gameplay concepts like board control and long-term planning. We study the progression of linear probe accuracy and tile color using both SAE's and linear probes to compare their effectiveness at capturing what the model is learning. Although we begin with a smaller language model, OthelloGPT, this study establishes a framework for understanding the internal representations learned by GPT models, transformers, and LLMs more broadly. Our code is publicly available: https://github.com/ALT-JS/OthelloSAE.

[Arxiv](https://arxiv.org/abs/2501.07108)