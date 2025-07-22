# 数据混合器：学习如何在持续预训练中重新调整各个领域的重要性

发布时间：2025年07月21日

`LLM理论

理由：这篇论文提出了一种新的解决方案，即数据混合代理，用于优化大型语言模型的持续预训练过程。该方法通过自动学习如何重新加权领域来解决灾难性遗忘问题，并通过强化学习掌握启发式规则。这涉及到模型的训练策略和优化方法，属于LLM的理论研究。` `数学推理` `代码生成`

> Data Mixing Agent: Learning to Re-weight Domains for Continual Pre-training

# 摘要

> 在小规模特定任务数据上进行持续预训练是优化大型语言模型在新目标领域性能的有效手段，但可能引发模型对原有能力的灾难性遗忘。为解决这一问题，一种常见方法是通过在领域空间中重新加权源领域和目标领域的训练数据混合，以实现性能平衡。然而，传统的领域重新加权策略往往依赖于基于人工直觉或经验结果的启发式手动指定。在本研究中，我们提出了一种全新的解决方案——数据混合代理（Data Mixing Agent），这是首个基于模型的端到端框架，能够自动学习如何重新加权领域。该代理通过在大量数据混合轨迹及其评估环境反馈中进行强化学习，掌握了具有普适性的启发式规则。实验结果表明，在数学推理任务的持续预训练中，数据混合代理在实现源领域和目标领域基准之间的平衡性能方面显著优于现有基线模型。更令人振奋的是，该方法无需重新训练即可很好地推广到未见过的源领域、目标模型和领域空间。将其直接应用于代码生成领域，进一步验证了其跨领域适应性的卓越表现。深入分析表明，数据混合代理所掌握的启发式规则不仅与人类直觉高度契合，而且能够在使用较少源领域数据的情况下，更高效地实现更优的模型性能。

> Continual pre-training on small-scale task-specific data is an effective method for improving large language models in new target fields, yet it risks catastrophic forgetting of their original capabilities. A common solution is to re-weight training data mixtures from source and target fields on a domain space to achieve balanced performance. Previous domain reweighting strategies rely on manual designation with certain heuristics based on human intuition or empirical results. In this work, we prove that more general heuristics can be parameterized by proposing Data Mixing Agent, the first model-based, end-to-end framework that learns to re-weight domains. The agent learns generalizable heuristics through reinforcement learning on large quantities of data mixing trajectories with corresponding feedback from an evaluation environment. Experiments in continual pre-training on math reasoning show that Data Mixing Agent outperforms strong baselines in achieving balanced performance across source and target field benchmarks. Furthermore, it generalizes well across unseen source fields, target models, and domain spaces without retraining. Direct application to the code generation field also indicates its adaptability across target domains. Further analysis showcases the agents' well-aligned heuristics with human intuitions and their efficiency in achieving superior model performance with less source-field data.

[Arxiv](https://arxiv.org/abs/2507.15640)