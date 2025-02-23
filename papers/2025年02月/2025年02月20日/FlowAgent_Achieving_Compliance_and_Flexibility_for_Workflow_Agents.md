# FlowAgent：为工作流代理达成合规性与灵活性

发布时间：2025年02月20日

`Agent` `自动化` `流程管理`

> FlowAgent: Achieving Compliance and Flexibility for Workflow Agents

# 摘要

> 工作流与大型语言模型（LLMs）的集成使LLM代理能够执行预定义的程序，从而提高现实世界应用中的自动化水平。然而，传统的基于规则的方法往往限制了LLMs的灵活性，特别是在处理意外的、工作流之外（OOW）的查询时。相比之下，基于提示的方法虽赋予LLMs完全控制流程的能力，却可能削弱程序合规性。为解决这些问题，我们推出了FlowAgent——一个创新的智能体框架，旨在平衡合规性与灵活性。我们提出了过程描述语言（PDL），它巧妙结合了自然语言的适应性和代码的精确性，用于定义工作流。基于PDL，我们构建了一个全面的框架，使LLMs能够有效处理OOW查询，同时确保执行路径在控制器的监督下运行。此外，我们引入了一种全新的评估方法，不仅测试LLM代理的常规流程合规性，还严格评估其处理OOW场景的能力。在三个数据集上的实验结果表明，FlowAgent在遵守工作流的同时，还能高效处理OOW查询，充分展现了其在合规性和灵活性方面的双重优势。代码可在GitHub上获取：https://github.com/Lightblues/FlowAgent。

> The integration of workflows with large language models (LLMs) enables LLM-based agents to execute predefined procedures, enhancing automation in real-world applications. Traditional rule-based methods tend to limit the inherent flexibility of LLMs, as their predefined execution paths restrict the models' action space, particularly when the unexpected, out-of-workflow (OOW) queries are encountered. Conversely, prompt-based methods allow LLMs to fully control the flow, which can lead to diminished enforcement of procedural compliance. To address these challenges, we introduce FlowAgent, a novel agent framework designed to maintain both compliance and flexibility. We propose the Procedure Description Language (PDL), which combines the adaptability of natural language with the precision of code to formulate workflows. Building on PDL, we develop a comprehensive framework that empowers LLMs to manage OOW queries effectively, while keeping the execution path under the supervision of a set of controllers. Additionally, we present a new evaluation methodology to rigorously assess an LLM agent's ability to handle OOW scenarios, going beyond routine flow compliance tested in existing benchmarks. Experiments on three datasets demonstrate that FlowAgent not only adheres to workflows but also effectively manages OOW queries, highlighting its dual strengths in compliance and flexibility. The code is available at https://github.com/Lightblues/FlowAgent.

[Arxiv](https://arxiv.org/abs/2502.14345)