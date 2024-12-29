# 自我引导的知识型思维网络：借助大型语言模型强化推理

发布时间：2024年12月21日

`LLM应用` `人工智能`

> Self-guided Knowledgeable Network of Thoughts: Amplifying Reasoning with Large Language Models

# 摘要

> 我们推出了知识型思维网络（kNoT）：这一提示方案让大型语言模型（LLM）的能力突破了现有的思维链（CoT）、思维树（ToT）和思维图（GoT）等范式。kNoT 的核心创新在于 LLM 工作流模板（LWT），它能让 LLM 为 LLM 制定可执行的计划。LWT 使得这些计划可以是任意网络，其中单步 LLM 操作是节点，边对应这些步骤间的消息传递。而且，LWT 通过索引支持单个元素的选择，助力 kNoT 生成复杂的计划，其中每个 LLM 操作能局限于基本操作，大幅提升了在扩展任务序列中的可靠性。我们表明，kNoT 在六个用例中表现显著优于现有水平，同时降低了对大量提示工程的需求。比如，在对 32 个数字进行排序时，kNoT 的准确率达 92%，而 ToT 和 GoT 分别为 12%和 31%，同时分别使用的特定任务提示少了多达 84.4%和 87.3%。

> We introduce Knowledgeable Network of Thoughts (kNoT): a prompt scheme that advances the capabilities of large language models (LLMs) beyond existing paradigms like Chain-of-Thought (CoT), Tree of Thoughts (ToT), and Graph of Thoughts (GoT). The key innovation of kNoT is the LLM Workflow Template (LWT), which allows for an executable plan to be specified by LLMs for LLMs. LWT allows these plans to be arbitrary networks, where single-step LLM operations are nodes, and edges correspond to message passing between these steps. Furthermore, LWT supports selection of individual elements through indexing, facilitating kNoT to produce intricate plans where each LLM operation can be limited to elementary operations, greatly enhancing reliability over extended task sequences. We demonstrate that kNoT significantly outperforms the state of the art on six use cases, while reducing the need for extensive prompt engineering. For instance, kNoT finds 92% accuracy for sorting 32 numbers over 12% and 31% for ToT and GoT, while utilizing up to 84.4% and 87.3% less task-specific prompts, respectively.

[Arxiv](https://arxiv.org/abs/2412.16533)