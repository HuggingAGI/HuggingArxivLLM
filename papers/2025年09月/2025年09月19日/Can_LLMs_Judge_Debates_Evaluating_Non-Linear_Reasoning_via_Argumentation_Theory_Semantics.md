# 大型语言模型（LLMs）能评判辩论吗？——基于论证理论语义学的非线性推理评估

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Can LLMs Judge Debates? Evaluating Non-Linear Reasoning via Argumentation Theory Semantics

# 摘要

> 大型语言模型（LLMs）擅长处理线性推理任务，却在非线性结构（如自然辩论中常见、最适合用论证图呈现的结构）上研究不足。我们探究LLMs能否模拟计算论证理论（CAT）中的结构化推理，具体采用定量论证辩论（QuAD）语义——该语义依据论证间的攻击与支持关系为其分配可接受性分数。研究仅提供两个NoDE数据集的对话式辩论文本，让模型在无法获取底层图结构的情况下对论证进行排序。我们在思维链（Chain-of-Thought）、上下文学习（In-Context Learning）等先进指令策略下测试了多个LLM。结果显示，模型与QuAD排名的一致性达到中等水平，但输入长度增加或语篇流中断时性能会下降。而先进提示策略通过减少论证长度和位置相关偏差，有效缓解了这些问题。研究结果揭示了LLM在建模形式化论证语义时的潜力与局限，也为未来图感知推理研究指明了方向。

> Large Language Models (LLMs) excel at linear reasoning tasks but remain underexplored on non-linear structures such as those found in natural debates, which are best expressed as argument graphs. We evaluate whether LLMs can approximate structured reasoning from Computational Argumentation Theory (CAT). Specifically, we use Quantitative Argumentation Debate (QuAD) semantics, which assigns acceptability scores to arguments based on their attack and support relations. Given only dialogue-formatted debates from two NoDE datasets, models are prompted to rank arguments without access to the underlying graph. We test several LLMs under advanced instruction strategies, including Chain-of-Thought and In-Context Learning. While models show moderate alignment with QuAD rankings, performance degrades with longer inputs or disrupted discourse flow. Advanced prompting helps mitigate these effects by reducing biases related to argument length and position. Our findings highlight both the promise and limitations of LLMs in modeling formal argumentation semantics and motivate future work on graph-aware reasoning.

[Arxiv](https://arxiv.org/abs/2509.15739)