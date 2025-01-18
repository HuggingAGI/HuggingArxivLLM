# AutoRestTest: 基于LLMs和MARL的REST API自动化测试工具

发布时间：2025年01月15日

`Agent

理由：这篇论文介绍了一个名为AutoRestTest的工具，该工具结合了语义操作依赖图（SODG）、多智能体强化学习（MARL）和大型语言模型（LLMs）来提升REST API测试效率。其中，多智能体强化学习（MARL）是核心组成部分，涉及多个智能体（操作、参数、值、依赖和头）的协作。因此，这篇论文主要关注的是智能体（Agent）的应用和开发，而不是纯粹的LLM理论、LLM应用或RAG（检索增强生成）技术。` `网络服务` `软件测试`

> AutoRestTest: A Tool for Automated REST API Testing Using LLMs and MARL

# 摘要

> 随着REST API在现代网络服务中的广泛应用，全面测试这些API变得至关重要。然而，由于操作、参数及其复杂依赖关系构成的巨大搜索空间，现有测试工具代码覆盖率低，故障检测效果不佳。为此，我们推出了AutoRestTest，一款结合语义操作依赖图（SODG）、多智能体强化学习（MARL）和大型语言模型（LLMs）的创新工具，旨在提升REST API测试效率。AutoRestTest通过SODG确定操作依赖的参数，并利用五个智能体（操作、参数、值、依赖和头）识别操作依赖关系，生成操作序列、参数组合和值。该工具提供命令行界面，实时监控成功操作数、检测到的服务器错误及耗时。测试完成后，AutoRestTest生成详细报告，列出检测到的错误和执行的操作。本文介绍了该工具并展示了初步成果。

> As REST APIs have become widespread in modern web services, comprehensive testing of these APIs has become increasingly crucial. Due to the vast search space consisting of operations, parameters, and parameter values along with their complex dependencies and constraints, current testing tools suffer from low code coverage, leading to suboptimal fault detection. To address this limitation, we present a novel tool, AutoRestTest, which integrates the Semantic Operation Dependency Graph (SODG) with Multi-Agent Reinforcement Learning (MARL) and large language models (LLMs) for effective REST API testing. AutoRestTest determines operation-dependent parameters using the SODG and employs five specialized agents (operation, parameter, value, dependency, and header) to identify dependencies of operations and generate operation sequences, parameter combinations, and values. AutoRestTest provides a command-line interface and continuous telemetry on successful operation count, unique server errors detected, and time elapsed. Upon completion, AutoRestTest generates a detailed report highlighting errors detected and operations exercised. In this paper, we introduce our tool and present preliminary results.

[Arxiv](https://arxiv.org/abs/2501.08600)