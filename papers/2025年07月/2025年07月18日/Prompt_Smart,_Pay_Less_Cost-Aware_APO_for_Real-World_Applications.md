# 聪明提示，少花钱：智能成本感知自动参数优化算法在现实应用中的应用

发布时间：2025年07月18日

`LLM应用` `人工智能`

> Prompt Smart, Pay Less: Cost-Aware APO for Real-World Applications

# 摘要

> 提示设计是大型语言模型 (LLMs) 实现有效性的关键因素，但目前仍主要依赖于启发式方法、手动操作且难以规模化。本文首次针对商业环境中真实、高风险的多类分类任务，全面评估了自动提示优化 (APO) 方法，填补了现有文献中的关键空白，因为大多数 APO 框架仅在复杂性有限的基准分类任务上得到验证。

我们引入了 APE-OPRO，一个结合 APE 和 OPRO 互补优势的新型混合框架，在不牺牲性能的前提下，实现了显著更好的成本效益，较 OPRO 提升了约 18%。我们在一个包含约 2,500 个标注产品的数据集上，将 APE-OPRO 与无梯度 (APE, OPRO) 和有梯度 (ProTeGi) 方法进行了基准测试。

我们的研究结果突显了关键的权衡：ProTeGi 在较低的 API 成本下提供了最强的绝对性能，但计算时间较高，如~\cite{protegi}中所指出的。而 APE-OPRO 在性能、API 效率和可扩展性之间达到了令人信服的平衡。我们进一步对深度和广度超参数进行了消融研究，并发现对标签格式有显著的敏感性，这表明了 LLM 行为中的隐式敏感性。这些发现为在商业应用中实施 APO 提供了可操作的见解，并为未来在多标签、视觉和多模态提示优化场景中的研究奠定了基础。

> Prompt design is a critical factor in the effectiveness of Large Language Models (LLMs), yet remains largely heuristic, manual, and difficult to scale. This paper presents the first comprehensive evaluation of Automatic Prompt Optimization (APO) methods for real-world, high-stakes multiclass classification in a commercial setting, addressing a critical gap in the existing literature where most of the APO frameworks have been validated only on benchmark classification tasks of limited complexity.
  We introduce APE-OPRO, a novel hybrid framework that combines the complementary strengths of APE and OPRO, achieving notably better cost-efficiency, around $18\%$ improvement over OPRO, without sacrificing performance. We benchmark APE-OPRO alongside both gradient-free (APE, OPRO) and gradient-based (ProTeGi) methods on a dataset of ~2,500 labeled products.
  Our results highlight key trade-offs: ProTeGi offers the strongest absolute performance at lower API cost but higher computational time as noted in~\cite{protegi}, while APE-OPRO strikes a compelling balance between performance, API efficiency, and scalability. We further conduct ablation studies on depth and breadth hyperparameters, and reveal notable sensitivity to label formatting, indicating implicit sensitivity in LLM behavior. These findings provide actionable insights for implementing APO in commercial applications and establish a foundation for future research in multi-label, vision, and multimodal prompt optimization scenarios.

[Arxiv](https://arxiv.org/abs/2507.15884)