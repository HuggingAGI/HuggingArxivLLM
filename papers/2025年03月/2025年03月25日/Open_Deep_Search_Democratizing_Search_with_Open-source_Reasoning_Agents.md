# # 开源深度搜索：让搜索更普惠，基于开源推理代理

发布时间：2025年03月25日

`LLM应用

理由：这篇论文主要介绍了如何通过引入推理代理（Agent）来增强开源大语言模型（LLM）的推理和搜索能力，特别是在实际任务中的应用表现。论文的重点在于LLM在具体任务中的应用和性能提升，因此归类到LLM应用。` `信息检索` `问答系统`

> Open Deep Search: Democratizing Search with Open-source Reasoning Agents

# 摘要

> 我们推出 Open Deep Search (ODS) 以缩小专有搜索AI解决方案（如 Perplexity 的 Sonar Reasoning Pro 和 OpenAI 的 GPT-4o Search Preview）与其开源替代方案之间的差距。ODS 的主要创新是通过引入能够审慎使用网络搜索工具的推理代理，增强最新开源大语言模型（LLM）的推理能力。具体来说，ODS 由两个与用户选择的基座 LLM 配合使用的组件构成：Open Search Tool 和 Open Reasoning Agent。Open Reasoning Agent 解释任务并通过编排一系列动作（包括调用工具，其中之一即为 Open Search Tool）来完成任务。Open Search Tool 是一种新型网络搜索工具，性能优于专有工具。与强大的开源推理大语言模型（如 DeepSeek-R1）结合使用时，ODS 在 SimpleQA 和 FRAMES 两个基准测试中几乎追平甚至超越现有最先进基线。例如，在 FRAMES 评估基准上，ODS 相对于近期发布的 GPT-4o Search Preview 的最佳现有基线，准确率提升了 9.7%。ODS 是一个通用框架，可无缝增强任何 LLM（例如 DeepSeek-R1 在 SimpleQA 上达到 82.4%，FRAMES 上达到 30.1%）的搜索和推理能力，实现最先进性能：SimpleQA 上的 88.3% 和 FRAMES 上的 75.3%。

> We introduce Open Deep Search (ODS) to close the increasing gap between the proprietary search AI solutions, such as Perplexity's Sonar Reasoning Pro and OpenAI's GPT-4o Search Preview, and their open-source counterparts. The main innovation introduced in ODS is to augment the reasoning capabilities of the latest open-source LLMs with reasoning agents that can judiciously use web search tools to answer queries. Concretely, ODS consists of two components that work with a base LLM chosen by the user: Open Search Tool and Open Reasoning Agent. Open Reasoning Agent interprets the given task and completes it by orchestrating a sequence of actions that includes calling tools, one of which is the Open Search Tool. Open Search Tool is a novel web search tool that outperforms proprietary counterparts. Together with powerful open-source reasoning LLMs, such as DeepSeek-R1, ODS nearly matches and sometimes surpasses the existing state-of-the-art baselines on two benchmarks: SimpleQA and FRAMES. For example, on the FRAMES evaluation benchmark, ODS improves the best existing baseline of the recently released GPT-4o Search Preview by 9.7% in accuracy. ODS is a general framework for seamlessly augmenting any LLMs -- for example, DeepSeek-R1 that achieves 82.4% on SimpleQA and 30.1% on FRAMES -- with search and reasoning capabilities to achieve state-of-the-art performance: 88.3% on SimpleQA and 75.3% on FRAMES.

[Arxiv](https://arxiv.org/abs/2503.20201)