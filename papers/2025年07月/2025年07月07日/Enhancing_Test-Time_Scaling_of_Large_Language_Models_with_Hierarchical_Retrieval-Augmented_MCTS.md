# # 分层检索增强蒙特卡洛树搜索提升大型语言模型测试时扩展
分层检索增强蒙特卡洛树搜索提升大型语言模型测试时扩展

发布时间：2025年07月07日

`LLM应用

理由：这篇论文提出了一种分层检索增强推理框架（R2-LLMs），用于提升大型语言模型在推理任务中的性能。它结合了检索和推理机制，优化了复杂推理任务中的准确度，属于LLM在实际应用中的改进和应用，因此归类为LLM应用。` `人工智能` `推理系统`

> Enhancing Test-Time Scaling of Large Language Models with Hierarchical Retrieval-Augmented MCTS

# 摘要

> 测试时缩放技术在语言建模领域展现出巨大潜力，通过在推理阶段调用额外计算资源来提升模型性能。本研究推出R2-LLMs，一个创新且灵活的分层检索增强推理框架，专为提升大型语言模型（LLMs）的测试时缩放能力而设计，无需从更先进的模型中蒸馏获取链式思维（CoT）训练数据。R2-LLMs通过双层次检索增强上下文学习，显著提升推理时的泛化能力：（1）在粗粒度层面，它从复杂推理问题中提取抽象模板，并检索相似的问题-答案对，促进高层次上下文学习；（2）在细粒度层面，它在蒙特卡洛树搜索（MCTS）过程中，从参考数学问题数据集中高效检索类似中间解题步骤，并借助过程奖励模型（PRM）进行评分，从而精炼分步推理过程。R2-LLMs是一个稳健的分层推理增强方法，既能强化上下文级别的推理能力，又能与分步级别的树搜索方法无缝衔接。通过利用PRM，它能够优化候选生成和决策过程，从而显著提升推理准确度。在MATH500、GSM8K和OlympiadBench-TO数据集上的实证评估表明，与基线模型相比，使用LLaMA-3.1-8B时，相对改进幅度最高可达16%，充分验证了我们在复杂推理任务中的方法有效性。


> Test-time scaling has emerged as a promising paradigm in language modeling, leveraging additional computational resources at inference time to enhance model performance. In this work, we introduce R2-LLMs, a novel and versatile hierarchical retrieval-augmented reasoning framework designed to improve test-time scaling in large language models (LLMs) without requiring distillation from more advanced models to obtain chain-of-thought (CoT) training data. R2-LLMs enhances inference-time generalization by integrating dual-level retrieval-based in-context learning: (1) At the coarse level, our approach extracts abstract templates from complex reasoning problems and retrieves similar problem-answer pairs to facilitate high-level in-context learning; (2) At the fine level, during Monte Carlo Tree Search (MCTS), R2-LLMs efficiently retrieves analogous intermediate solution steps from reference mathematical problem datasets, refining step-wise reasoning with the aid of a process reward model (PRM) for scoring. R2-LLMs is a robust hierarchical reasoning-augmentation method that enhances in-context-level reasoning while seamlessly integrating with step-level tree search methods. Utilizing PRM, it refines both candidate generation and decision-making for improved reasoning accuracy. Empirical evaluations on the MATH500, GSM8K, and OlympiadBench-TO datasets achieve substantial relative improvement with an increase of up to 16% using LLaMA-3.1-8B compared to the baselines, showcasing the effectiveness of our approach in complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2507.05557)