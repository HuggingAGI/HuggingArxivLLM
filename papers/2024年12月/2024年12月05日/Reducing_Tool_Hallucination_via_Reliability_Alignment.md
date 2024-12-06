# 借助可靠性对齐来降低工具幻觉

发布时间：2024年12月05日

`LLM应用` `语言模型` `工具调用`

> Reducing Tool Hallucination via Reliability Alignment

# 摘要

> 大型语言模型（LLMs）的能力已不止于语言生成，还能通过工具调用与外部系统交互，为实际应用带来强大潜能。然而，模型不当选择或误用工具时出现的工具幻觉现象，带来了重大挑战，可能致使任务执行出错、运营成本上升。本文探讨了可靠工具调用的概念，强调了解决工具幻觉的必要性。我们把工具幻觉系统地归为两大类：工具选择幻觉和工具使用幻觉。为减轻这些问题，我们提出了一个注重可靠性的对齐框架，增强模型准确评估工具相关性和使用情况的能力。通过提出一系列评估指标，并在 StableToolBench 上进行评估，进一步证明了我们的框架在减轻工具幻觉、提高 LLM 工具调用的整体系统可靠性方面的成效。

> Large Language Models (LLMs) have extended their capabilities beyond language generation to interact with external systems through tool calling, offering powerful potential for real-world applications. However, the phenomenon of tool hallucinations, which occur when models improperly select or misuse tools, presents critical challenges that can lead to flawed task execution and increased operational costs. This paper investigates the concept of reliable tool calling and highlights the necessity of addressing tool hallucinations. We systematically categorize tool hallucinations into two main types: tool selection hallucination and tool usage hallucination. To mitigate these issues, we propose a reliability-focused alignment framework that enhances the model's ability to accurately assess tool relevance and usage. By proposing a suite of evaluation metrics and evaluating on StableToolBench, we further demonstrate the effectiveness of our framework in mitigating tool hallucination and improving the overall system reliability of LLM tool calling.

[Arxiv](https://arxiv.org/abs/2412.04141)