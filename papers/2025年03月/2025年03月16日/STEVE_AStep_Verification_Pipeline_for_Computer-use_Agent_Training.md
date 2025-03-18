# STEVE：用于计算机使用代理训练的逐步验证流水线

发布时间：2025年03月16日

`Agent` `计算机使用代理` `人机交互`

> STEVE: AStep Verification Pipeline for Computer-use Agent Training

# 摘要

> 开发能够自主操作图形用户界面的AI代理是一项长期具有挑战性的任务。近期在数据扩展定律方面的进展启发我们使用扩展的指令集训练计算机使用代理，然而，使用行为克隆训练代理仍然需要大量高质量的轨迹数据。为了满足可扩展性的需求，我们设计了STEVE，这是一个用于计算机使用代理训练的分步验证管道。首先，我们为计算机使用代理建立了一个大型指令集，并通过一些次优代理收集轨迹数据。GPT-4o被用来根据动作执行前后屏幕验证轨迹中每一步的正确性，并为每一步分配二进制标签。最后，我们采用Kahneman和Tversky优化方法，根据二进制分步标签优化代理。大量实验表明，我们的代理通过利用轨迹中的正向和负向动作，性能优于监督微调。此外，STEVE使我们能够训练一个7B规模的视觉-语言模型作为计算机使用代理，在具有挑战性的实时桌面环境WinAgentArena中实现了卓越性能，同时以更低的成本实现了高效的训练。代码和数据：https://github.com/FanbinLu/STEVE.

> Developing AI agents to autonomously manipulate graphical user interfaces is a long challenging task. Recent advances in data scaling law inspire us to train computer-use agents with a scaled instruction set, yet using behavior cloning to train agents still requires immense high-quality trajectories. To meet the scalability need, we designed STEVE, a step verification pipeline for computer-use agent training. First, we establish a large instruction set for computer-use agents and collect trajectory data with some suboptimal agents. GPT-4o is used to verify the correctness of each step in the trajectories based on the screens before and after the action execution, assigning each step with a binary label. Last, we adopt the Kahneman and Tversky Optimization to optimize the agent from the binary stepwise labels. Extensive experiments manifest that our agent outperforms supervised finetuning by leveraging both positive and negative actions within a trajectory. Also, STEVE enables us to train a 7B vision-language model as a computer-use agent, achieving leading performance in the challenging live desktop environment WinAgentArena with great efficiency at a reduced cost. Code and data: https://github.com/FanbinLu/STEVE.

[Arxiv](https://arxiv.org/abs/2503.12532)