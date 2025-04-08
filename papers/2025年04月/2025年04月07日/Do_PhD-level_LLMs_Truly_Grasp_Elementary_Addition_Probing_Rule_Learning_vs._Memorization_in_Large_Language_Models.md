# 大型语言模型是否真的理解基础加法？探析博士级模型中的规则学习与记忆机制

发布时间：2025年04月07日

`LLM理论`

> Do PhD-level LLMs Truly Grasp Elementary Addition? Probing Rule Learning vs. Memorization in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在基准测试中表现优异，但它们在简单问题上频频失误，这引发了一个关键疑问：LLMs 是真正掌握了数学原理，还是仅仅记忆了模式？与近期研究设计日益复杂的基准测试不同，我们通过基本的两整数加法（$0$ 至 $2^{64}$）来探究这一问题，重点关注两个核心属性：交换律（$A+B=B+A$）和组合泛化能力（通过同构符号映射实现，例如 $7 ightarrow y$）。尽管当前最优的 LLMs 在数值加法上的准确率可达 73.8-99.8%，但在符号映射条件下，准确率骤降至 $\leq$7.5%，这表明模型未能有效泛化所学规则。此外，算术性能随数字位数增长呈现非单调变化，且频繁出现交换律失效（超过 1,700 例 $A+B 
eq B+A$），进一步印证了这一结论。值得注意的是，显式提供加法规则会导致性能平均下降 81.2%，而模型自解释能力则能保持基准准确率，这表明 LLM 的算术处理机制与人类定义的数学原则存在显著偏差。我们的研究结果表明，当前 LLMs 更依赖于记忆模式，而非真正掌握规则，这凸显了模型架构的局限性，并呼吁开发新的方法以实现真正的数学推理能力。

> Despite high benchmark scores, Large Language Models (LLMs) often fail simple problem, raising a critical question: Do LLMs learn mathematical principles or merely memorize patterns? Rather than designing increasingly complex benchmarks like recent works, we investigate this using elementary two-integer addition ($0$ to $2^{64}$), probing two core properties: commutativity ($A+B=B+A$) and compositional generalization (via isomorphic symbolic mappings, e.g., $7 \rightarrow y$). While state-of-the-art LLMs achieve 73.8-99.8\% accuracy on numerical addition, performance collapses to $\leq$7.5\% under symbolic mapping, indicating failure to generalize learned rules. Non-monotonic performance scaling with digit count and frequent commutativity violations (over 1,700 cases of $A+B \neq B+A$) further support this. Explicitly providing addition rules degrades performance by 81.2\% on average, while self-explanation maintains baseline accuracy, suggesting LLM arithmetic processing is misaligned with human-defined principles. Our findings indicate current LLMs rely on memory pattern over genuine rule learning, highlighting architectural limitations and the need for new approaches to achieve true mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2504.05262)