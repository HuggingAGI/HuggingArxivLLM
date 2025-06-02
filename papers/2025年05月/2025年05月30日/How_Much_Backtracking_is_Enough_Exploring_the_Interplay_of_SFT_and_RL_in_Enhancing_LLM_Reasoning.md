# 回溯多少才算够？探索SFT与RL如何协同提升LLM推理能力

发布时间：2025年05月30日

`LLM理论` `人工智能`

> How Much Backtracking is Enough? Exploring the Interplay of SFT and RL in Enhancing LLM Reasoning

# 摘要

> 大型语言模型（LLMs）近期在推理能力上取得了显著突破，尤其在数学和逻辑问题领域，这得益于监督微调（SFT）和强化学习（RL）等技术的应用。先前研究表明，强化学习能够有效内化搜索策略，支持长链式推理（CoT），并且回溯作为一种学习能力自然浮现。然而，回溯的具体优势及其对推理能力提升的贡献仍不明确。本研究聚焦于SFT与RL在八个推理任务中的交互作用，包括倒计时、数独、几何、颜色立方体旋转等。研究发现，SFT阶段使用短CoT序列作为预热训练对RL训练有一定促进作用，但随着任务难度增加，这种作用逐渐减弱。为此，我们构建了系统性改变回溯步骤数量的合成数据集，并通过控制实验分别探究了正确性（内容）或结构（回溯频率）的影响。发现显示：（1）带有回溯的长链式推理能促进更优且稳定的RL训练；（2）复杂问题往往需要在SFT阶段采用更多回溯步骤。此外，实验表明RL对长CoT序列的正确性不敏感，更关注结构模式。这些发现为设计提升LLMs推理能力的最优训练策略提供了实用见解。

> Recent breakthroughs in large language models (LLMs) have effectively improved their reasoning abilities, particularly on mathematical and logical problems that have verifiable answers, through techniques such as supervised finetuning (SFT) and reinforcement learning (RL). Prior research indicates that RL effectively internalizes search strategies, enabling long chain-of-thought (CoT) reasoning, with backtracking emerging naturally as a learned capability. However, the precise benefits of backtracking, specifically, how significantly it contributes to reasoning improvements and the optimal extent of its use, remain poorly understood. In this work, we systematically investigate the dynamics between SFT and RL on eight reasoning tasks: Countdown, Sudoku, Arc 1D, Geometry, Color Cube Rotation, List Functions, Zebra Puzzles, and Self Reference. Our findings highlight that short CoT sequences used in SFT as a warm-up do have moderate contribution to RL training, compared with cold-start RL; however such contribution diminishes when tasks become increasingly difficult. Motivated by this observation, we construct synthetic datasets varying systematically in the number of backtracking steps and conduct controlled experiments to isolate the influence of either the correctness (content) or the structure (i.e., backtrack frequency). We find that (1) longer CoT with backtracks generally induce better and more stable RL training, (2) more challenging problems with larger search space tend to need higher numbers of backtracks during the SFT stage. Additionally, we demonstrate through experiments on distilled data that RL training is largely unaffected by the correctness of long CoT sequences, suggesting that RL prioritizes structural patterns over content correctness. Collectively, our results offer practical insights into designing optimal training strategies to effectively scale reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2505.24273)