# 面向参数高效大型语言模型的结构可学习适配器微调

发布时间：2025年09月03日

`LLM理论` `基础理论`

> Structure-Learnable Adapter Fine-Tuning for Parameter-Efficient Large Language Models

# 摘要

> 本文聚焦大型语言模型微调中的参数冗余、结构僵化及任务适应性不足等痛点，提出了一种基于结构可学习机制的适配器微调方法。该方法引入可微门控函数与结构稀疏控制变量，实现了适配器插入点、激活路径及模块组合的自动优化，从而让模型在多任务场景中灵活调整结构，精准适配不同任务特性。在主干参数冻结的前提下，该方法借助结构搜索机制，在训练阶段动态构建任务专属的高效子结构，有效提升了参数利用率与表征能力。此外，本文还设计了敏感性分析实验，系统评估了稀疏权重、噪声注入率及数据扰动对模型性能的影响。实验结果证实，该方法在多任务自然语言理解任务中具备良好的稳定性与鲁棒性。最终实验显示，该方法在多项任务上性能超越主流参数高效调优技术，在准确性、压缩率及抗噪声与抗扰动能力之间达成了更优平衡。

> This paper addresses the issues of parameter redundancy, rigid structure, and limited task adaptability in the fine-tuning of large language models. It proposes an adapter-based fine-tuning method built on a structure-learnable mechanism. By introducing differentiable gating functions and structural sparsity control variables, the method enables automatic optimization of adapter insertion points, activation paths, and module combinations. This allows the model to adjust its structure flexibly in multi-task settings to match different task characteristics. With the backbone parameters kept frozen, the method uses a structure search mechanism to guide the dynamic construction of task-specific efficient substructures during training. This significantly improves parameter utilization and representational capacity. In addition, the paper designs a set of sensitivity analysis experiments to systematically evaluate the effects of sparsity weight, noise injection ratio, and data perturbation on model performance. These experiments verify the stability and robustness of the proposed method across various multi-task natural language understanding tasks. The experimental results show that the proposed method outperforms mainstream parameter-efficient tuning techniques on multiple tasks. It achieves a better balance among accuracy, compression rate, and robustness to noise and perturbation.

[Arxiv](https://arxiv.org/abs/2509.03057)