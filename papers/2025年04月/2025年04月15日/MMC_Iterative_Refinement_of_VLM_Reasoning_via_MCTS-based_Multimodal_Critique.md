# MMC：通过多模态批判实现 VLM 推理的迭代优化

发布时间：2025年04月15日

`LLM应用` `多模态` `多模态推理`

> MMC: Iterative Refinement of VLM Reasoning via MCTS-based Multimodal Critique

# 摘要

> 视觉语言模型（VLMs）在多模态推理任务中表现出色，但幻觉等挑战仍会导致推理错误。受大型语言模型（LLMs）中外部反馈机制的启发，我们提出了多模态Actor-Critic框架，以增强VLM的推理能力。具体来说，Actor模型基于图像和文本生成逐步推理路径，而Critic模型则评估这些路径并提供反馈。Actor模型根据反馈不断优化推理，直到Critic模型满意为止。为减少人工标注成本，我们提出了构建多模态批判数据集的自动化方法。通过蒙特卡洛树搜索（MCTS），我们引导Actor模型系统地探索多样推理路径。我们还设计了标注模型比较从同一祖先节点发散的两条推理路径——一条通向正确结论，另一条则通向错误结论，从而获得批判数据。基于此，我们构建了基于MCTS的多模态批判（MMC）数据集，并开发了全面的训练和推理pipeline。在多个公共基准数据集和主流VLM上的实验表明，我们的方法显著提升了复杂多模态推理任务的性能，证明了其有效性和广泛应用前景。

> Visual language models (VLMs) have demonstrated strong performance across diverse multimodal reasoning tasks but still face challenges such as hallucinations, resulting in incorrect reasoning outcomes. Inspired by recent research on external feedback mechanisms in large language models (LLMs), we propose a multimodal actor-critic framework to enhance VLM reasoning capabilities. Specifically, the actor model generates step-by-step reasoning paths based on image and text inputs, while the critic model evaluates these reasoning paths and provides corrective feedback. The actor model iteratively refines its reasoning based on the feedback until the reasoning outcome is deemed satisfactory by the critic model. To reduce reliance on costly manual annotations, we introduce an automated method for constructing multimodal critique datasets. By leveraging Monte Carlo Tree Search (MCTS), we systematically guide the actor model to explore diverse reasoning paths. To obtain critique data for correcting erroneous reasoning steps, we prompt an annotator model to compare pairs of reasoning paths diverging from a shared ancestor node - one leading to a correct conclusion and the other to an incorrect one. This approach enables us to construct the MMC (MCTS-based Multimodal Critique) dataset, upon which we further develop a comprehensive training and inference pipeline. Extensive experiments conducted on several public benchmark datasets and mainstream VLMs demonstrate that our approach significantly improves the performance of VLM on complex multimodal reasoning tasks, underscoring its effectiveness and wide applicability.

[Arxiv](https://arxiv.org/abs/2504.11009)