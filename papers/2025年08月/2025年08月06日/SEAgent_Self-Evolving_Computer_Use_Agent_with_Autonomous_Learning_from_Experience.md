# SEAgent：一款能够自主学习、自我演进的计算机使用代理，通过经验不断进化

发布时间：2025年08月06日

`Agent` `计算机使用代理` `软件自动化`

> SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience

# 摘要

> 将大型视觉语言模型（LVLMs）重新用于计算机使用代理（CUA）已经带来了显著的突破，但这些进展主要依赖于人类标注的数据。然而，这些模型在面对新颖且专业的软件时常常表现不佳，尤其是在缺乏人类标注的情况下。为了解决这一挑战，我们提出了SEAgent，这是一个自主演化的框架，使CUA能够通过与不熟悉软件的交互自主进化。具体来说，SEAgent赋能计算机使用代理通过经验学习自主掌握新的软件环境，其中代理探索新软件，通过迭代试错学习，并逐步解决从简单到复杂自动组织的任务。为了实现这一目标，我们设计了一个用于分步轨迹评估的世界状态模型，以及一个生成日益多样化和具有挑战性任务的课程生成器。代理的策略通过经验学习进行更新，包括对失败动作的对抗模仿和对成功动作的组相对策略优化（GRPO）。此外，我们引入了一种从专家到通才的训练策略，整合了专家代理的个体经验见解，从而促进更强的通才CUA的发展，该CUA能够实现持续的自主进化。这个统一的代理最终在特定软件上的表现超过了个体专家代理的集成。我们在OS-World的五个新软件环境中验证了SEAgent的有效性。我们的方法在成功率方面取得了显著提升，从11.3%提升到34.5%，相比一个具有竞争力的开源CUA（即UI-TARS）提高了23.2%。

> Repurposing large vision-language models (LVLMs) as computer use agents (CUAs) has led to substantial breakthroughs, primarily driven by human-labeled data. However, these models often struggle with novel and specialized software, particularly in scenarios lacking human annotations. To address this challenge, we propose SEAgent, an agentic self-evolving framework enabling CUAs to autonomously evolve through interactions with unfamiliar software. Specifically, SEAgent empowers computer-use agents to autonomously master novel software environments via experiential learning, where agents explore new software, learn through iterative trial-and-error, and progressively tackle auto-generated tasks organized from simple to complex. To achieve this goal, we design a World State Model for step-wise trajectory assessment, along with a Curriculum Generator that generates increasingly diverse and challenging tasks. The agent's policy is updated through experiential learning, comprised of adversarial imitation of failure actions and Group Relative Policy Optimization (GRPO) on successful ones. Furthermore, we introduce a specialist-to-generalist training strategy that integrates individual experiential insights from specialist agents, facilitating the development of a stronger generalist CUA capable of continuous autonomous evolution. This unified agent ultimately achieves performance surpassing ensembles of individual specialist agents on their specialized software. We validate the effectiveness of SEAgent across five novel software environments within OS-World. Our approach achieves a significant improvement of 23.2% in success rate, from 11.3% to 34.5%, over a competitive open-source CUA, i.e., UI-TARS.

[Arxiv](https://arxiv.org/abs/2508.04700)