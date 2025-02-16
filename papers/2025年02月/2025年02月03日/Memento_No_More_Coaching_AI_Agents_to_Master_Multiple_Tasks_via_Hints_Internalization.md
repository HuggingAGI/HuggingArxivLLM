# 记忆不再：通过内化提示，训练AI代理掌握多种任务

发布时间：2025年02月03日

`Agent` `AI代理` `多任务学习`

> Memento No More: Coaching AI Agents to Master Multiple Tasks via Hints Internalization

# 摘要

> 随着AI代理能力的不断提升，如何通过经验掌握多个复杂任务仍是关键挑战。当前基于LLM的代理，尤其是专有语言模型驱动的代理，通常依赖提示语来整合目标任务的知识，却无法真正内化这些信息，只能通过不断扩展提示语来维持功能，就像一个患有顺行性遗忘症的人依赖笔记系统。在本文中，我们提出了一种全新方法，使AI代理无需繁琐的笔记系统或高质量演示数据，即可整合多任务知识与技能。我们的方法通过迭代过程，让代理在收集新经验的同时，接收人类以提示形式的反馈，并通过上下文蒸馏训练整合反馈。我们通过在Llama-3代理中实现这一方法，仅经过几轮反馈，便在需要正确排序信息检索、工具使用和问答的任务中，超越了GPT-4o和DeepSeek-V3等先进模型。

> As the general capabilities of artificial intelligence (AI) agents continue to evolve, their ability to learn to master multiple complex tasks through experience remains a key challenge. Current LLM agents, particularly those based on proprietary language models, typically rely on prompts to incorporate knowledge about the target tasks. This approach does not allow the agent to internalize this information and instead relies on ever-expanding prompts to sustain its functionality in diverse scenarios. This resembles a system of notes used by a person affected by anterograde amnesia, the inability to form new memories. In this paper, we propose a novel method to train AI agents to incorporate knowledge and skills for multiple tasks without the need for either cumbersome note systems or prior high-quality demonstration data. Our approach employs an iterative process where the agent collects new experiences, receives corrective feedback from humans in the form of hints, and integrates this feedback into its weights via a context distillation training procedure. We demonstrate the efficacy of our approach by implementing it in a Llama-3-based agent which, after only a few rounds of feedback, outperforms advanced models GPT-4o and DeepSeek-V3 in a taskset requiring correct sequencing of information retrieval, tool use, and question answering.

[Arxiv](https://arxiv.org/abs/2502.01562)