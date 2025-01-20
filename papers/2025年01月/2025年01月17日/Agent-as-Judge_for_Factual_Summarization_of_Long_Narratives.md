# 智能体作为法官：长叙述的事实性摘要

发布时间：2025年01月17日

`Agent

理由：这篇论文提出了一个名为NarrativeFactScore的“Agent-as-a-Judge”框架，用于评估大型语言模型生成摘要的事实一致性。该框架通过提取角色知识图（CKG）来评估事实一致性，并提供改进建议。这种方法强调了代理（Agent）在评估和改进LLM生成内容中的作用，因此应归类为Agent。` `摘要生成`

> Agent-as-Judge for Factual Summarization of Long Narratives

# 摘要

> 大型语言模型（LLMs）在摘要任务中表现出接近人类的性能，但传统指标如ROUGE和BERTScore无法充分衡量事实准确性，尤其是对于长篇叙述（>100K tokens）。尽管LLM-as-a-Judge等新方法弥补了词汇相似性指标的不足，但在理解角色关系和状态时仍存在事实不一致的问题。为此，我们提出了NarrativeFactScore，一种创新的“Agent-as-a-Judge”框架，通过从输入和生成的摘要中提取角色知识图（CKG）来评估事实一致性，并提供改进建议，如识别缺失或错误的事实。我们通过详细的工作流程和广泛验证证明了NarrativeFactScore的有效性，其在多个基准测试中表现优于现有方法。结果表明，代理驱动评估系统有望显著提升LLM生成摘要的事实可靠性。

> Large Language Models (LLMs) have demonstrated near-human performance in summarization tasks based on traditional metrics such as ROUGE and BERTScore. However, these metrics do not adequately capture critical aspects of summarization quality, such as factual accuracy, particularly for long narratives (>100K tokens). Recent advances, such as LLM-as-a-Judge, address the limitations of metrics based on lexical similarity but still exhibit factual inconsistencies, especially in understanding character relationships and states. In this work, we introduce NarrativeFactScore, a novel "Agent-as-a-Judge" framework for evaluating and refining summaries. By leveraging a Character Knowledge Graph (CKG) extracted from input and generated summaries, NarrativeFactScore assesses the factual consistency and provides actionable guidance for refinement, such as identifying missing or erroneous facts. We demonstrate the effectiveness of NarrativeFactScore through a detailed workflow illustration and extensive validation on widely adopted benchmarks, achieving superior performance compared to competitive methods. Our results highlight the potential of agent-driven evaluation systems to improve the factual reliability of LLM-generated summaries.

[Arxiv](https://arxiv.org/abs/2501.09993)