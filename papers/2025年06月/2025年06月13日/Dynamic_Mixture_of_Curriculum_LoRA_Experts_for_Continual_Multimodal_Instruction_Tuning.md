# 动态混合课程LoRA专家模型，实现持续多模态指令微调。

发布时间：2025年06月13日

`LLM理论` `多模态` `模型进化`

> Dynamic Mixture of Curriculum LoRA Experts for Continual Multimodal Instruction Tuning

# 摘要

> 持续的多模态指令微调在适应多模态大型语言模型（MLLMs）不断演变的任务中发挥着关键作用。然而，现有方法大多采用固定架构，导致模型容量静态化，难以适应新任务。我们提出了一种基于参数预算的动态架构调整方法，以实现任务的动态适应。这一创新方向尚未被探索，且面临两大挑战：1) 任务架构冲突，不同任务需要逐层不同的适应方式；2) 模态不平衡，不同任务对模态的依赖程度不一，导致更新失衡。为应对这些挑战，我们提出了一种名为动态课程LoRA专家混合方法（D-MoLE）的新方法。该方法通过受控参数预算自动进化MLLM架构，在持续适应新任务的同时保留已学知识。具体而言，我们设计了一种动态逐层专家分配器，自动跨层分配LoRA专家以解决架构冲突，并通过逐层路由指令促进专家间知识共享。此外，我们提出了一种基于梯度的跨模态持续课程方法，根据任务中各模态的难度调整MLLM中各模块的更新比例，从而有效缓解模态不平衡问题。大量实验结果表明，D-MoLE显著超越现有最优基线，平均性能提升达15%。据我们所知，这是首个从架构角度研究MLLM持续学习的研究工作。


> Continual multimodal instruction tuning is crucial for adapting Multimodal Large Language Models (MLLMs) to evolving tasks. However, most existing methods adopt a fixed architecture, struggling with adapting to new tasks due to static model capacity. We propose to evolve the architecture under parameter budgets for dynamic task adaptation, which remains unexplored and imposes two challenges: 1) task architecture conflict, where different tasks require varying layer-wise adaptations, and 2) modality imbalance, where different tasks rely unevenly on modalities, leading to unbalanced updates. To address these challenges, we propose a novel Dynamic Mixture of Curriculum LoRA Experts (D-MoLE) method, which automatically evolves MLLM's architecture with controlled parameter budgets to continually adapt to new tasks while retaining previously learned knowledge. Specifically, we propose a dynamic layer-wise expert allocator, which automatically allocates LoRA experts across layers to resolve architecture conflicts, and routes instructions layer-wisely to facilitate knowledge sharing among experts. Then, we propose a gradient-based inter-modal continual curriculum, which adjusts the update ratio of each module in MLLM based on the difficulty of each modality within the task to alleviate the modality imbalance problem. Extensive experiments show that D-MoLE significantly outperforms state-of-the-art baselines, achieving a 15% average improvement over the best baseline. To the best of our knowledge, this is the first study of continual learning for MLLMs from an architectural perspective.

[Arxiv](https://arxiv.org/abs/2506.11672)