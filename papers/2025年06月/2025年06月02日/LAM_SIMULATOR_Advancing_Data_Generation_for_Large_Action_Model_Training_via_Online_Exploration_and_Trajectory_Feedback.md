# LAM模拟器：通过在线探索与轨迹反馈助力大型动作模型训练的数据生成

发布时间：2025年06月02日

`LLM应用` `AI代理` `数据科学`

> LAM SIMULATOR: Advancing Data Generation for Large Action Model Training via Online Exploration and Trajectory Feedback

# 摘要

> 大型动作模型（LAMs）为AI代理带来了巨大潜力，但高质量训练数据的获取，尤其是涉及规划、工具调用和反馈响应的多步骤任务，仍面临挑战。为解决这一难题，我们推出了LAM SIMULATOR——一个专为具身任务设计的在线探索框架，能够提供高质量反馈。该框架内置动态任务查询生成器、丰富工具库以及交互式环境，使大型语言模型（LLM）代理能够调用工具并实时接收反馈，从而自主探索和解决问题，发现多种应对策略。生成的动作轨迹数据可用于创建高质量训练集，助力LAMs的训练。在ToolBench和CRMArena等流行具身基准测试中，LAM SIMULATOR表现出色：基于自动生成数据集训练的模型性能大幅提升，最高可达49.3%的提升。值得注意的是，LAM SIMULATOR在数据集创建过程中仅需极少量人工干预，充分展现了其在加速AI代理开发中的高效与实用。

> Large Action Models (LAMs) for AI Agents offer incredible potential but face challenges due to the need for high-quality training data, especially for multi-steps tasks that involve planning, executing tool calls, and responding to feedback. To address these issues, we present LAM SIMULATOR, a comprehensive framework designed for online exploration of agentic tasks with high-quality feedback. Our framework features a dynamic task query generator, an extensive collection of tools, and an interactive environment where Large Language Model (LLM) Agents can call tools and receive real-time feedback. This setup enables LLM Agents to explore and solve tasks autonomously, facilitating the discovery of multiple approaches to tackle any given task. The resulting action trajectory data are then used to create high-quality training datasets for LAMs. Our experiments on popular agentic benchmarks, ToolBench and CRMArena, highlight the effectiveness of LAM SIMULATOR: models trained with self-generated datasets using our framework achieve significant performance gains, up to a 49.3\% improvement over their original baselines. LAM SIMULATOR requires minimal human input during dataset creation, highlighting LAM SIMULATOR's efficiency and effectiveness in speeding up development of AI agents.

[Arxiv](https://arxiv.org/abs/2506.02298)