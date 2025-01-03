# MobileSafetyBench: 移动设备控制中自主代理的安全性评估

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了由大型语言模型（LLMs）驱动的自主代理在移动设备控制中的应用，特别是如何评估和提升这些代理在安全性方面的表现。论文提出了一个名为MobileSafetyBench的基准测试，用于评估移动设备控制代理的安全性，并设计了一系列任务来测试代理在处理潜在风险时的表现。此外，论文还提出了一种提示方法，旨在鼓励代理优先考虑安全因素。这些内容都与自主代理（Agent）的设计、评估和改进密切相关，因此将其分类为Agent是合适的。` `移动设备` `安全性评估`

> MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control

# 摘要

> # 摘要
由大型语言模型（LLMs）驱动的自主代理在移动设备控制等领域的辅助任务中展现出巨大潜力。由于这些代理直接处理个人信息和设备设置，确保其行为安全可靠至关重要。然而，目前尚缺乏评估移动设备控制代理安全性的标准化基准。为此，我们推出了MobileSafetyBench，这是一个基于Android模拟器的真实移动环境中的安全性评估基准。我们设计了一系列任务，涵盖与消息和银行等移动应用的交互。为了明确区分安全性和有用性，我们分别设计了安全性任务和有用性任务。安全性任务挑战代理处理日常生活中的潜在风险，并测试其对间接提示注入的鲁棒性。实验表明，尽管基于最先进LLMs的基线代理在执行有用任务时表现出色，但在安全性任务中表现欠佳。为此，我们提出了一种提示方法，鼓励代理优先考虑安全因素。虽然该方法在促进安全行为方面显示出潜力，但要完全赢得用户信任，仍需进一步改进。这突显了在移动环境中开发更强大安全机制的迫切需求。我们的基准已在以下网址开源：https://mobilesafetybench.github.io/。

> Autonomous agents powered by large language models (LLMs) show promising potential in assistive tasks across various domains, including mobile device control. As these agents interact directly with personal information and device settings, ensuring their safe and reliable behavior is crucial to prevent undesirable outcomes. However, no benchmark exists for standardized evaluation of the safety of mobile device-control agents. In this work, we introduce MobileSafetyBench, a benchmark designed to evaluate the safety of device-control agents within a realistic mobile environment based on Android emulators. We develop a diverse set of tasks involving interactions with various mobile applications, including messaging and banking applications. To clearly evaluate safety apart from general capabilities, we design separate tasks measuring safety and tasks evaluating helpfulness. The safety tasks challenge agents with managing potential risks prevalent in daily life and include tests to evaluate robustness against indirect prompt injections. Our experiments demonstrate that while baseline agents, based on state-of-the-art LLMs, perform well in executing helpful tasks, they show poor performance in safety tasks. To mitigate these safety concerns, we propose a prompting method that encourages agents to prioritize safety considerations. While this method shows promise in promoting safer behaviors, there is still considerable room for improvement to fully earn user trust. This highlights the urgent need for continued research to develop more robust safety mechanisms in mobile environments. We open-source our benchmark at: https://mobilesafetybench.github.io/.

[Arxiv](https://arxiv.org/abs/2410.17520)