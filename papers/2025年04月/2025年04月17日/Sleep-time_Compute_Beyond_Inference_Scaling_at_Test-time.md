# 睡眠计算：突破测试时推理扩展的界限

发布时间：2025年04月17日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）在智能体软件工程任务中的应用，特别是通过“睡眠时间计算”方法优化推理过程。虽然优化推理计算属于应用层面，但案例研究明确涉及智能体系统，因此归类为Agent。` `智能体软件工程` `软件工程`

> Sleep-time Compute: Beyond Inference Scaling at Test-time

# 摘要

> 在大型语言模型（LLMs）中，扩展推理计算能力已成为解决复杂问题的关键因素，但同时也带来了高延迟和高昂的推理成本。我们引入了“睡眠时间计算”（sleep-time compute），使模型能够在查询呈现之前“离线思考”上下文：通过预判用户可能提出的问题并预先计算有用的数据，我们能够显著减少推理阶段所需的计算资源。为了验证我们方法的有效性，我们创建了两个推理任务的修改版本——Stateful GSM-Symbolic 和 Stateful AIME。我们发现，“睡眠时间计算”能够将实现相同准确率所需的推理计算量减少约 5 倍（在 Stateful GSM-Symbolic 和 Stateful AIME 任务中），并且通过扩展“睡眠时间计算”，我们还能进一步将准确率提升 13%（在 Stateful GSM-Symbolic 中）和 18%（在 Stateful AIME 中）。此外，我们引入了 Multi-Query GSM-Symbolic，它通过在每个上下文中包含多个相关查询扩展了 GSM-Symbolic。通过利用 Multi-Query GSM-Symbolic 在同一上下文的多个相关查询之间分摊“睡眠时间计算”成本，我们能够将每个查询的平均成本降低 2.5 倍。随后，我们进行了额外的分析，以了解“睡眠时间计算”在何时最为有效，发现用户查询的可预测性与“睡眠时间计算”的效果密切相关。最后，我们对将“睡眠时间计算”应用于一个实际的智能体软件工程（agentic SWE）任务进行了案例研究。

> Scaling test-time compute has emerged as a key ingredient for enabling large language models (LLMs) to solve difficult problems, but comes with high latency and inference cost. We introduce sleep-time compute, which allows models to "think" offline about contexts before queries are presented: by anticipating what queries users might ask and pre-computing useful quantities, we can significantly reduce the compute requirements at test-time. To demonstrate the efficacy of our method, we create modified versions of two reasoning tasks - Stateful GSM-Symbolic and Stateful AIME. We find that sleep-time compute can reduce the amount of test-time compute needed to achieve the same accuracy by ~ 5x on Stateful GSM-Symbolic and Stateful AIME and that by scaling sleep-time compute we can further increase accuracy by up to 13% on Stateful GSM-Symbolic and 18% on Stateful AIME. Furthermore, we introduce Multi-Query GSM-Symbolic, which extends GSM-Symbolic by including multiple related queries per context. By amortizing sleep-time compute across related queries about the same context using Multi-Query GSM-Symbolic, we can decrease the average cost per query by 2.5x. We then conduct additional analysis to understand when sleep-time compute is most effective, finding the predictability of the user query to be well correlated with the efficacy of sleep-time compute. Finally, we conduct a case-study of applying sleep-time compute to a realistic agentic SWE task.

[Arxiv](https://arxiv.org/abs/2504.13171)