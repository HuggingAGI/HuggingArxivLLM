# 循序渐进：自我激活稀疏混合排序自适应学习实现持续学习

发布时间：2025年06月26日

`LLM理论` `计算机视觉`

> Little By Little: Continual Learning via Self-Activated Sparse Mixture-of-Rank Adaptive Learning

# 摘要

> 持续学习（CL）与大型预训练模型结合时，面临着灾难性遗忘和任务干扰的挑战。现有的基于LoRA的专家混合模型（MoE）通过分配并冻结特定任务的适配器来减轻遗忘，但因适配器级别选择过于粗放而面临干扰、冗余和路由模糊的问题。我们提出MoRA，一种基于自我激活和稀疏秩激活的细粒度秩自适应学习方法，适用于持续学习。MoRA将每个秩r更新分解为r个独立的秩1组件，每个组件作为独立专家，实现秩1专家的精细混合利用，同时缓解干扰和冗余。结合秩剪枝和激活预算方法，MoRA为每个输入自适应地选择稀疏的秩混合。我们在CLIP和大型语言模型（LLMs）上的持续学习任务中验证了MoRA，分析了微调过程中的跨域学习和跨域遗忘/泛化表现。MoRA在提升PTM的持续学习效果、增强泛化能力的同时显著缓解了遗忘问题。


> Continual learning (CL) with large pre-trained models is challenged by catastrophic forgetting and task interference. Existing LoRA-based Mixture-of-Experts (MoE) approaches mitigate forgetting by assigning and freezing task-specific adapters, but suffer from interference, redundancy, and ambiguous routing due to coarse adapter-level selection. However, this design introduces three key challenges: 1) Interference: Activating full LoRA experts per input leads to subspace interference and prevents selective reuse of useful components across tasks. 2) Redundancy: Newly added experts often duplicate or contradict existing knowledge due to unnecessary activation of unrelated ranks and insufficient reuse of relevant ones. 3) Ambiguity: Overlapping features across tasks confuse the router, resulting in unstable expert assignments. As more experts accumulate, earlier task routing degrades, accelerating forgetting. We propose MoRA, a Mixture-of-Rank Adaptive learning approach with self-activated and sparse rank activation for CL. Unlike mixing multiple low-rank matrices, MoRA decomposes each rank-r update into r rank-1 components, each treated as an independent expert, enabling fine-grained mixture of rank-1 expert utilization while mitigating interference and redundancy. To avoid ambiguous routing, we propose that each rank-1 expert can infer its own relevance via intermediate activations. Coupled with our proposed rank pruning and activation budgets, MoRA adaptively selects a sparse mixture of ranks per input. We validate MoRA on continual learning tasks with CLIP and large language models (LLMs), analyzing both in-domain learning and out-of-domain forgetting/generalization during fine-tuning. MoRA shows significant effectiveness on enhancing CL with PTMs, and improving generalization while mitigating forgetting.

[Arxiv](https://arxiv.org/abs/2506.21035)