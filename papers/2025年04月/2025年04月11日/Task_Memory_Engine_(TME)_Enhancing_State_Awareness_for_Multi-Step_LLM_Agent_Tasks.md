# 任务记忆引擎 (TME)：提升多步骤 LLM 代理任务的状态感知能力

发布时间：2025年04月11日

`Agent

摘要中讨论了将大型语言模型（LLMs）用作自主代理，并提出了一种新的任务记忆引擎（TME）来改善其任务执行能力。这属于自主代理的设计和架构，因此归类为Agent。` `任务执行` `多步骤代理`

> Task Memory Engine (TME): Enhancing State Awareness for Multi-Step LLM Agent Tasks

# 摘要

> 大型语言模型（LLMs）正日益被用作多步骤任务的自主代理。然而，现有大多数框架未能保持对任务状态的结构化理解，通常依赖于线性提示拼接或浅层内存缓冲区，导致了脆弱的性能表现、频繁的幻觉生成以及较差的长程连贯性。为解决这一问题，我们提出了任务记忆引擎（TME），一个轻量级且结构化的内存模块。TME通过层级化的任务记忆树（TMT）来追踪任务执行过程，其中每个节点对应一个任务步骤，存储相关输入、输出、状态及子任务关系。我们还引入了一种提示合成方法，能够基于活跃节点路径动态生成LLM提示，从而显著提升执行一致性和上下文关联性。通过多步骤代理任务的案例研究和对比实验，我们证明了TME在实现更高任务完成准确性和更可解释的行为方面具有显著优势，且实施开销极低。TME的完整实现可在https://github.com/biubiutomato/TME-Agent获取。

> Large Language Models (LLMs) are increasingly used as autonomous agents for multi-step tasks. However, most existing frameworks fail to maintain a structured understanding of the task state, often relying on linear prompt concatenation or shallow memory buffers. This leads to brittle performance, frequent hallucinations, and poor long-range coherence. In this work, we propose the Task Memory Engine (TME), a lightweight and structured memory module that tracks task execution using a hierarchical Task Memory Tree (TMT). Each node in the tree corresponds to a task step, storing relevant input, output, status, and sub-task relationships. We introduce a prompt synthesis method that dynamically generates LLM prompts based on the active node path, significantly improving execution consistency and contextual grounding. Through case studies and comparative experiments on multi-step agent tasks, we demonstrate that TME leads to better task completion accuracy and more interpretable behavior with minimal implementation overhead. The full implementation of TME is available at https://github.com/biubiutomato/TME-Agent.

[Arxiv](https://arxiv.org/abs/2504.08525)