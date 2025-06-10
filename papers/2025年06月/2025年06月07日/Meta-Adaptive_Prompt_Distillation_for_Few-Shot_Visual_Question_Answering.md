# # 面向少量样本视觉问答的元自适应提示蒸馏

发布时间：2025年06月07日

`LLM应用` `视觉问答` `多模态`

> Meta-Adaptive Prompt Distillation for Few-Shot Visual Question Answering

# 摘要

> 大模型（LMMs）通常依赖于上下文学习（ICL）来在最小监督下执行新任务。然而，ICL的表现，尤其是在较小的LMMs中，并不稳定，并且随着示例数量的增加，并不总是单调提升。我们假设这是因为LMM被下游任务不需要的图像嵌入中的额外信息所淹没。为了解决这一问题，我们提出了一种元学习方法，该方法使用一组固定的软提示来诱导LMMs的少样本能力，这些软提示是从与任务相关的图像特征中蒸馏出来的，并且可以在测试时使用少量示例进行适应。为了促进这种蒸馏，我们引入了一个注意力映射模块，该模块可以轻松集成到流行的LLaVA v1.5架构中，并与软提示一起学习，从而在低数据环境下仅需几步梯度更新即可实现任务适应。在VL-ICL Bench上的评估表明，我们的方法在图像扰动下仍然优于ICL和相关提示微调方法，改善了视觉问答任务中的任务诱导和推理能力。

> Large Multimodal Models (LMMs) often rely on in-context learning (ICL) to perform new tasks with minimal supervision. However, ICL performance, especially in smaller LMMs, is inconsistent and does not always improve monotonically with increasing examples. We hypothesize that this occurs due to the LMM being overwhelmed by additional information present in the image embeddings, which is not required for the downstream task. To address this, we propose a meta-learning approach that provides an alternative for inducing few-shot capabilities in LMMs, using a fixed set of soft prompts that are distilled from task-relevant image features and can be adapted at test time using a few examples. To facilitate this distillation, we introduce an attention-mapper module that can be easily integrated with the popular LLaVA v1.5 architecture and is jointly learned with soft prompts, enabling task adaptation in LMMs under low-data regimes with just a few gradient steps. Evaluation on the VL-ICL Bench shows that our method consistently outperforms ICL and related prompt-tuning approaches, even under image perturbations, improving task induction and reasoning across visual question answering tasks.

[Arxiv](https://arxiv.org/abs/2506.06905)