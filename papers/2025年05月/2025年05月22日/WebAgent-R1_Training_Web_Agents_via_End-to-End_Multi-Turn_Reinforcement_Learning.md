# # **WebAgent-R1：通过端到端多轮强化学习构建Web智能体**

发布时间：2025年05月22日

`Agent` `网络自动化` `Web自动化`

> WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning

# 摘要

> 尽管强化学习 (RL) 在提升大型语言模型 (LLMs) 方面表现突出，但其应用主要局限于单轮任务，如数学问题解决。面对动态网页界面中的长周期决策和多轮交互，训练有效的网络代理仍具挑战。本研究提出了一种简单而高效的端到端多轮 RL 框架——WebAgent-R1，专为训练网络代理而设计。该框架通过异步生成多样化轨迹，直接从与网络环境的在线交互中学习，完全依赖于任务成功的二元奖励。在 WebArena-Lite 基准测试中，WebAgent-R1 展现了卓越性能，使 Qwen-2.5-3B 的任务成功率从 6.1% 提升至 33.9%，Llama-3.1-8B 的成功率从 8.5% 提升至 44.8%，远超 OpenAI o3 等现有先进方法和强大多用途模型。深入分析表明，基于思考的提示策略和通过增加交互次数进行测试时缩放在 Web 任务中尤为有效。此外，我们通过引入两种变体 WebAgent-R1-Zero 和 WebAgent-R1-CoT，进一步探讨了不同 RL 初始化策略，突显了暖机训练阶段（即行为克隆）的重要性，并为在 Web 代理中整合长链式推理提供了重要见解。

> While reinforcement learning (RL) has demonstrated remarkable success in enhancing large language models (LLMs), it has primarily focused on single-turn tasks such as solving math problems. Training effective web agents for multi-turn interactions remains challenging due to the complexity of long-horizon decision-making across dynamic web interfaces. In this work, we present WebAgent-R1, a simple yet effective end-to-end multi-turn RL framework for training web agents. It learns directly from online interactions with web environments by asynchronously generating diverse trajectories, entirely guided by binary rewards depending on task success. Experiments on the WebArena-Lite benchmark demonstrate the effectiveness of WebAgent-R1, boosting the task success rate of Qwen-2.5-3B from 6.1% to 33.9% and Llama-3.1-8B from 8.5% to 44.8%, significantly outperforming existing state-of-the-art methods and strong proprietary models such as OpenAI o3. In-depth analyses reveal the effectiveness of the thinking-based prompting strategy and test-time scaling through increased interactions for web tasks. We further investigate different RL initialization policies by introducing two variants, namely WebAgent-R1-Zero and WebAgent-R1-CoT, which highlight the importance of the warm-up training stage (i.e., behavior cloning) and provide insights on incorporating long chain-of-thought (CoT) reasoning in web agents.

[Arxiv](https://arxiv.org/abs/2505.16421)