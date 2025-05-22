# 辩论、训练、进化：语言模型的自我推理进化

发布时间：2025年05月21日

`LLM理论` `人工智能`

> DEBATE, TRAIN, EVOLVE: Self Evolution of Language Model Reasoning

# 摘要

> 大型语言模型（LLMs）通过海量数据的训练，推理能力显著提升。然而，单纯依赖数据驱动的改进已显局限，模型自主提升推理能力的需求日益凸显。本文提出了一种名为“辩论、训练、进化”（DTE）的创新无真实标签训练框架，利用多智能体的辩论轨迹来进化单一语言模型。同时，我们引入“反思-批判-精进”的新提示策略，通过引导智能体批判和优化推理过程，显著提升辩论质量。在五个推理基准测试中，基于六种开源权重模型的评估显示，我们的 DTE 框架表现优异，尤其在 GSM-PLUS 数据集上平均准确率提升 8.92%。此外，实验还展现了强大的跨领域泛化能力，在所有其他基准测试中平均准确率提升 5.8%，表明该方法成功捕捉到了通用推理能力。

> Large language models (LLMs) have improved significantly in their reasoning through extensive training on massive datasets. However, relying solely on additional data for improvement is becoming increasingly impractical, highlighting the need for models to autonomously enhance their reasoning without external supervision. In this paper, we propose Debate, Train, Evolve (DTE), a novel ground truth-free training framework that uses multi-agent debate traces to evolve a single language model. We also introduce a new prompting strategy Reflect-Critique-Refine, to improve debate quality by explicitly instructing agents to critique and refine their reasoning. Extensive evaluations on five reasoning benchmarks with six open-weight models show that our DTE framework achieve substantial improvements, with an average accuracy gain of 8.92% on the challenging GSM-PLUS dataset. Furthermore, we observe strong cross-domain generalization, with an average accuracy gain of 5.8% on all other benchmarks, suggesting that our method captures general reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2505.15734)