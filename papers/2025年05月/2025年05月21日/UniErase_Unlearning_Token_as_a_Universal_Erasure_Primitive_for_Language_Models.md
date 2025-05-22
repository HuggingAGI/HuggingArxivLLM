# UniErase：语言模型的通用擦除原语——遗忘标记

发布时间：2025年05月21日

`LLM理论` `人工智能`

> UniErase: Unlearning Token as a Universal Erasure Primitive for Language Models

# 摘要

> 大型语言模型需要迭代更新来应对知识冲突和过时信息等挑战（例如错误、私密或非法内容）。机器遗忘为从训练模型中系统地移除特定知识提供了一种方法，能够消除敏感信息的影响。然而，主流的基于微调的遗忘方法常常无法平衡遗忘效果与模型能力，导致在大规模知识移除时模型出现灾难性崩溃。与此同时，仅依赖上下文提示而没有修改模型内在机制的上下文遗忘方法存在泛化能力有限的问题，难以实现真正的遗忘。在这项研究中，我们提出了UniErase，一种全新的遗忘范式，它通过可学习的参数化后缀（遗忘标记）引导语言模型实现定向遗忘行为。UniErase的工作流程分为两个关键阶段：(I) 优化阶段，通过标记优化将期望的遗忘输出与模型的自回归概率分布绑定，随后是(II) 轻量级模型编辑阶段，激活学习到的标记以概率方式诱导指定的遗忘目标。作为标记学习诱导遗忘目标的新研究方向，UniErase在批量、序列和精确遗忘方面，在虚构和现实世界知识设置下均实现了最先进的（SOTA）性能。值得注意的是，在TOFU基准测试中，UniErase仅修改了LLM参数的约3.66%，在模型能力上比之前的遗忘SOTA基线高出约4.01倍，同时保持了更好的遗忘效果。同样，UniErase在保持更多能力的同时，其遗忘效果也比之前的保留SOTA高出35.96%，在当前的遗忘领域中展现了双一流性能。

> Large language models require iterative updates to address challenges such as knowledge conflicts and outdated information (e.g., incorrect, private, or illegal contents). Machine unlearning provides a systematic methodology for targeted knowledge removal from trained models, enabling elimination of sensitive information influences. However, mainstream fine-tuning-based unlearning methods often fail to balance unlearning efficacy and model ability, frequently resulting in catastrophic model collapse under extensive knowledge removal. Meanwhile, in-context unlearning, which relies solely on contextual prompting without modifying the model's intrinsic mechanisms, suffers from limited generalizability and struggles to achieve true unlearning. In this work, we introduce UniErase, a novel unlearning paradigm that employs learnable parametric suffix (unlearning token) to steer language models toward targeted forgetting behaviors. UniErase operates through two key phases: (I) an optimization stage that binds desired unlearning outputs to the model's autoregressive probability distribution via token optimization, followed by (II) a lightweight model editing phase that activates the learned token to probabilistically induce specified forgetting objective. Serving as a new research direction for token learning to induce unlearning target, UniErase achieves state-of-the-art (SOTA) performance across batch, sequential, and precise unlearning under fictitious and real-world knowledge settings. Remarkably, in terms of TOFU benchmark, UniErase, modifying only around 3.66% of the LLM parameters, outperforms previous forgetting SOTA baseline by around 4.01 times for model ability with even better unlearning efficacy. Similarly, UniErase, maintaining more ability, also surpasses previous retaining SOTA by 35.96% for unlearning efficacy, showing dual top-tier performances in current unlearing domain.

[Arxiv](https://arxiv.org/abs/2505.15674)