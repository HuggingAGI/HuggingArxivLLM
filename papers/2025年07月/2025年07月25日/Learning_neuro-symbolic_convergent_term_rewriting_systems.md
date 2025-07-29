# 学习神经符号收敛项重写系统

发布时间：2025年07月25日

`其他

其他` `人工智能`

> Learning neuro-symbolic convergent term rewriting systems

# 摘要

> 在人工智能领域，构建能够学习执行符号算法的神经系统是一个极具挑战性的开放问题，尤其是在追求强泛化能力和分布外性能方面。本文提出了一种基于神经符号架构的通用框架，该架构灵感来源于重写算法本身，用于学习收敛的项重写系统。我们展示了这种架构的两个模块化实现：神经重写系统 (NRS) 和快速神经重写系统 (FastNRS)。得益于算法启发的设计和关键架构元素，两个模型均能够泛化到分布外实例，其中FastNRS在内存效率、训练速度和推理时间方面均实现了显著提升。我们在涉及数学公式简化的四项任务上对两种架构进行了评估，并进一步在多领域学习场景中展示了它们的 versatility，其中单个模型被训练以同时解决多种类型的问题。所提出的系统在与两个强大的神经基线模型的对比中表现显著优于前者：近期专门设计用于解决算法问题的神经数据路由器（一种新型变压器变体），以及功能强大的通用大型语言模型 GPT-4o。此外，我们的系统在与 OpenAI 最新推出的 o1-preview 模型的对比中也达到了匹配或超越其性能的水平，该模型在推理基准测试中表现优异。

> Building neural systems that can learn to execute symbolic algorithms is a challenging open problem in artificial intelligence, especially when aiming for strong generalization and out-of-distribution performance. In this work, we introduce a general framework for learning convergent term rewriting systems using a neuro-symbolic architecture inspired by the rewriting algorithm itself. We present two modular implementations of such architecture: the Neural Rewriting System (NRS) and the Fast Neural Rewriting System (FastNRS). As a result of algorithmic-inspired design and key architectural elements, both models can generalize to out-of-distribution instances, with FastNRS offering significant improvements in terms of memory efficiency, training speed, and inference time. We evaluate both architectures on four tasks involving the simplification of mathematical formulas and further demonstrate their versatility in a multi-domain learning scenario, where a single model is trained to solve multiple types of problems simultaneously. The proposed system significantly outperforms two strong neural baselines: the Neural Data Router, a recent transformer variant specifically designed to solve algorithmic problems, and GPT-4o, one of the most powerful general-purpose large-language models. Moreover, our system matches or outperforms the latest o1-preview model from OpenAI that excels in reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2507.19372)