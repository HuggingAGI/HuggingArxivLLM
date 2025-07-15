# # 通过自动化测试生成评估 LLMs 的顺序 API 调用能力

发布时间：2025年07月12日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在整合外部API工具后的应用潜力，并提出了一个自动化框架StateGen来生成涉及顺序API交互的任务，以测试和评估这些模型。论文的重点在于实际应用中的测试和评估，属于LLM应用领域。` `API工具` `软件工程`

> Evaluating LLMs on Sequential API Call Through Automated Test Generation

# 摘要

> 通过整合外部API工具，大型语言模型（LLMs）在复杂现实任务中的潜力得到了显著扩展。然而，对于LLM工具使用的测试、评估和分析仍处于早期阶段。现有基准测试依赖手动收集的测试用例，且大多无法自动验证语义正确性，仅能通过字符串匹配等静态方法完成。此外，这些基准测试往往忽视真实应用场景中常见的顺序API调用之间的复杂交互。为解决这一问题，本文提出了StateGen——一个用于生成涉及顺序API交互的多样化编码任务的自动化框架。StateGen通过结合基于状态机的API约束求解与验证、能量采样以及控制流注入，生成可执行程序。这些程序随后通过两个LLM代理的协作，转化为人类自然语言的任务描述。借助StateGen，我们构建了StateEval基准测试，涵盖跨越三个代表性场景（会话服务、张量操作和ElevenLabs MCP）的120个经过验证的测试用例。实验结果证实，StateGen能够有效生成具有挑战性和现实意义的API导向任务，凸显了当前集成API的LLMs在哪些方面还有提升空间。

> By integrating tools from external APIs, Large Language Models (LLMs) have expanded their promising capabilities in a diverse spectrum of complex real-world tasks. However, testing, evaluation, and analysis of LLM tool use remain in their early stages. Most existing benchmarks rely on manually collected test cases, many of which cannot be automatically checked for semantic correctness and instead depend on static methods such as string matching. Additionally, these benchmarks often overlook the complex interactions that occur between sequential API calls, which are common in real-world applications. To fill the gap, in this paper, we introduce StateGen, an automated framework designed to generate diverse coding tasks involving sequential API interactions. StateGen combines state-machine-based API constraint solving and validation, energy-based sampling, and control-flow injection to generate executable programs. These programs are then translated into human-like natural language task descriptions through a collaboration of two LLM agents. Utilizing StateGen, we construct StateEval, a benchmark encompassing 120 verified test cases spanning across three representative scenarios: Session Service, Tensor Operation, and ElevenLabs MCP. Experimental results confirm that StateGen can effectively generate challenging and realistic API-oriented tasks, highlighting areas for improvement in current LLMs incorporating APIs.

[Arxiv](https://arxiv.org/abs/2507.09481)