# EMORL：集成多目标强化学习实现高效灵活的LLM微调

发布时间：2025年05月05日

`LLM应用

理由：这篇论文探讨了强化学习在大型语言模型微调中的应用，特别是在多目标任务上的解决方案。它提出了一种名为Ensemble Multi-Objective RL（EMORL）的框架，并在心理咨询师回应生成任务上进行了评估，展示了其在实际应用中的优势。因此，这篇论文属于LLM应用类别。` `心理健康` `心理咨询`

> EMORL: Ensemble Multi-Objective Reinforcement Learning for Efficient and Flexible LLM Fine-Tuning

# 摘要

> 强化学习（RL）在大型语言模型（LLM）微调中的最新进展为多目标任务提供了有潜力的解决方案，但仍然面临诸多挑战，如复杂的多目标平衡、训练效率低下、扩展性不足和可解释性有限。我们基于集成学习原则，提出了一种名为Ensemble Multi-Objective RL（EMORL）的框架。该框架通过为多个模型分别设定个体目标进行微调，并在训练后优化它们的聚合效果，从而提升效率和灵活性。我们的方法首次聚合了个体模型的最后一个隐藏层状态，结合多目标的上下文信息。这一创新得到了分层网格搜索算法的支持，用于识别最优加权组合。我们在心理咨询师回应生成任务上评估了EMORL，利用文本评分的LLMs评估生成结果并在RL微调过程中提供奖励。通过在PAIR和Psych8k数据集上的全面实验，我们展示了EMORL相对于现有基线的显著优势：更低且更稳定的训练消耗（17,529±1,650个数据点和6,573±147.43秒），更优的扩展性和可解释性，以及在多个目标上可比的性能表现。

> Recent advances in reinforcement learning (RL) for large language model (LLM) fine-tuning show promise in addressing multi-objective tasks but still face significant challenges, including complex objective balancing, low training efficiency, poor scalability, and limited explainability. Leveraging ensemble learning principles, we introduce an Ensemble Multi-Objective RL (EMORL) framework that fine-tunes multiple models with individual objectives while optimizing their aggregation after the training to improve efficiency and flexibility. Our method is the first to aggregate the last hidden states of individual models, incorporating contextual information from multiple objectives. This approach is supported by a hierarchical grid search algorithm that identifies optimal weighted combinations. We evaluate EMORL on counselor reflection generation tasks, using text-scoring LLMs to evaluate the generations and provide rewards during RL fine-tuning. Through comprehensive experiments on the PAIR and Psych8k datasets, we demonstrate the advantages of EMORL against existing baselines: significantly lower and more stable training consumption ($17,529\pm 1,650$ data points and $6,573\pm 147.43$ seconds), improved scalability and explainability, and comparable performance across multiple objectives.

[Arxiv](https://arxiv.org/abs/2505.02579)