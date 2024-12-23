# 对大型语言模型的组合关系推理进行基准测试与理解

发布时间：2024年12月17日

`LLM应用` `语言模型` `推理任务`

> Benchmarking and Understanding Compositional Relational Reasoning of LLMs

# 摘要

> 组合关系推理（CRR）乃人类智慧的显著特征，然而我们并不明确现有的 Transformer 大型语言模型（LLMs）能否以及怎样解决 CRR 任务。为了对 LLMs 的 CRR 能力展开系统性探索，我们先是在统一框架中整合并概括机械可解释性（MI）研究里若干任务的精髓，提出了一个名为广义联想回忆（GAR）的全新综合基准。评估显示，GAR 对于现有的 LLMs 颇具挑战性，暴露了它们在 CRR 方面的根本缺陷。同时，它对于系统性的 MI 研究而言又足够简便。接着，为弄明白 LLMs 如何解决 GAR 任务，我们运用归因修补来找出 Vicuna-33B 在不同任务中复用的核心电路以及一组关键的注意力头。干预实验表明，这些头的正常运作对任务表现影响显著。尤其值得一提的是，我们确定了两类头，它们的激活分别代表了 GAR 任务中真和假的抽象概念。它们在各类模型和任务的 CRR 中发挥着基础性作用。数据集和代码可在 https://github.com/Caiyun-AI/GAR 获取。

> Compositional relational reasoning (CRR) is a hallmark of human intelligence, but we lack a clear understanding of whether and how existing transformer large language models (LLMs) can solve CRR tasks. To enable systematic exploration of the CRR capability of LLMs, we first propose a new synthetic benchmark called Generalized Associative Recall (GAR) by integrating and generalizing the essence of several tasks in mechanistic interpretability (MI) study in a unified framework. Evaluation shows that GAR is challenging enough for existing LLMs, revealing their fundamental deficiency in CRR. Meanwhile, it is easy enough for systematic MI study. Then, to understand how LLMs solve GAR tasks, we use attribution patching to discover the core circuits reused by Vicuna-33B across different tasks and a set of vital attention heads. Intervention experiments show that the correct functioning of these heads significantly impacts task performance. Especially, we identify two classes of heads whose activations represent the abstract notion of true and false in GAR tasks respectively. They play a fundamental role in CRR across various models and tasks. The dataset and code are available at https://github.com/Caiyun-AI/GAR.

[Arxiv](https://arxiv.org/abs/2412.12841)