# CL-MoE: 通过双动量专家混合模型强化多模态大型语言模型，实现持续视觉问答能力

发布时间：2025年03月01日

`LLM应用` `视觉问答` `计算机视觉`

> CL-MoE: Enhancing Multimodal Large Language Model with Dual Momentum Mixture-of-Experts for Continual Visual Question Answering

# 摘要

> 多模态大型语言模型（MLLMs）凭借其在视觉语言任务（如视觉问答）中的出色表现，引发了研究界的广泛关注。然而，现实世界中知识的快速更新使得MLLMs的离线训练成本高昂，且在处理非平稳数据流时，模型会面临灾难性遗忘的挑战。为此，我们提出了一种基于MLLMs的双动量专家混合模型（CL-MoE）框架，用于持续视觉问答（VQA）。我们结合MLLMs与持续学习，充分利用大型语言模型中的丰富常识。通过引入双路由专家混合模型（RMoE）策略，我们利用任务级和实例级路由器选择全局和局部专家，确保为最适合任务的专家分配稳健权重。随后，我们设计了动态动量专家混合模型（MMoE），根据专家与任务/实例之间的关系动态更新专家参数，使模型在吸收新知识的同时保持现有知识。实验结果表明，我们的方法在10个VQA任务中实现了最先进的性能，充分证明了其有效性。

> Multimodal large language models (MLLMs) have garnered widespread attention from researchers due to their remarkable understanding and generation capabilities in visual language tasks (e.g., visual question answering). However, the rapid pace of knowledge updates in the real world makes offline training of MLLMs costly, and when faced with non-stationary data streams, MLLMs suffer from catastrophic forgetting during learning. In this paper, we propose an MLLMs-based dual momentum Mixture-of-Experts (CL-MoE) framework for continual visual question answering (VQA). We integrate MLLMs with continual learning to utilize the rich commonsense knowledge in LLMs. We introduce a Dual-Router MoE (RMoE) strategy to select the global and local experts using task-level and instance-level routers, to robustly assign weights to the experts most appropriate for the task. Then, we design a dynamic Momentum MoE (MMoE) to update the parameters of experts dynamically based on the relationships between the experts and tasks/instances, so that the model can absorb new knowledge while maintaining existing knowledge. The extensive experimental results indicate that our method achieves state-of-the-art performance on 10 VQA tasks, proving the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2503.00413)