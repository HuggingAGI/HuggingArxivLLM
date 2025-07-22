# WebShaper：主动式数据合成的实现方法——信息寻求形式化

发布时间：2025年07月20日

`Agent` `信息检索` `人工智能`

> WebShaper: Agentically Data Synthesizing via Information-Seeking Formalization

# 摘要

> 大型语言模型（LLM）驱动的智能体通过基于网络的信息检索（IS）能力，使人工智能能够解决复杂、开放性的任务，从而实现了革命性的变革。然而，高质量训练数据的稀缺性限制了IS智能体的发展。现有方法通常采用信息驱动的范式，首先收集网络数据，然后基于检索生成问题，这可能导致信息结构与推理结构、问题与答案之间的不一致。为了解决这一问题，我们提出了一种形式化驱动的IS数据合成框架WebShaper。WebShaper通过集合论系统地形式化IS任务，其核心是知识投影（KP）的概念，它通过KP操作组合实现了对推理结构的精准控制。在合成过程中，我们首先创建种子任务，然后使用多步扩展过程。在每一步中，一个智能的扩展器基于我们的形式化，利用检索和验证工具将当前形式化的问题扩展得更加复杂。我们使用合成的数据集对模型进行训练。实验结果表明，WebShaper在GAIA和WebWalkerQA基准测试中，达到了开源IS智能体的最新技术水平。

> The advent of Large Language Model (LLM)-powered agents has revolutionized artificial intelligence by enabling solutions to complex, open-ended tasks through web-based information-seeking (IS) capabilities. The scarcity of high-quality training data has limited the development of IS agents. Existing approaches typically adopt an information-driven paradigm that first collects web data and then generates questions based on the retrieval. However, this may lead to inconsistency between information structure and reasoning structure, question and answer. To mitigate, we propose a formalization-driven IS data synthesis framework WebShaper to construct a dataset. WebShaper systematically formalizes IS tasks through set theory. Central to the formalization is the concept of Knowledge Projections (KP), which enables precise control over reasoning structure by KP operation compositions. During synthesis, we begin by creating seed tasks, then use a multi-step expansion process. At each step, an agentic Expander expands the current formal question more complex with retrieval and validation tools based on our formalization. We train our model on the synthesized dataset. Experiment results demonstrate that WebShaper achieves state-of-the-art performance among open-sourced IS agents on GAIA and WebWalkerQA benchmarks.

[Arxiv](https://arxiv.org/abs/2507.15061)