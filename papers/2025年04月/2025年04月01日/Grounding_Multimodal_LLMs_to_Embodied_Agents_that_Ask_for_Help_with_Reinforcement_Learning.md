# 多模态大语言模型与具身智能体的结合：利用强化学习主动寻求帮助

发布时间：2025年04月01日

`Agent` `机器人` `智能体`

> Grounding Multimodal LLMs to Embodied Agents that Ask for Help with Reinforcement Learning

# 摘要

> 在现实环境中操作的具身智能体必须能够解释模糊且不充分的人类指令。一个功能强大的家用机器人应该能够识别模糊性，并提出相关的问题以澄清用户意图，从而更有效地执行任务。为了研究这一问题，我们引入了Ask-to-Act任务，其中具身智能体必须在家庭环境中根据模糊指令获取特定物体实例。智能体必须在部分可观察性条件下，战略性地提出最少但相关的澄清问题以解决模糊性。为了解决这个问题，我们提出了一种新颖的方法，该方法通过使用基于LLM生成奖励的在线强化学习（RL）对多模态大型语言模型（MLLMs）进行微调，将其作为视觉-语言-动作（VLA）策略。我们的方法消除了在训练此类智能体时需要大规模人类演示或手动设计奖励的需求。我们在我们的任务上与强大的零样本基线进行了比较，包括GPT-4o和监督微调的MLLMs。我们的结果表明，我们的RL微调MLLM显著优于所有基线（19.1%-40.3%），并且很好地推广到新的场景和任务。据我们所知，这是首次演示将MLLMs适应为VLA智能体，能够使用基于LLM生成的奖励通过在线RL进行行动和寻求帮助。

> Embodied agents operating in real-world environments must interpret ambiguous and under-specified human instructions. A capable household robot should recognize ambiguity and ask relevant clarification questions to infer the user intent accurately, leading to more effective task execution. To study this problem, we introduce the Ask-to-Act task, where an embodied agent must fetch a specific object instance given an ambiguous instruction in a home environment. The agent must strategically ask minimal, yet relevant, clarification questions to resolve ambiguity while navigating under partial observability. To solve this problem, we propose a novel approach that fine-tunes multimodal large language models (MLLMs) as vision-language-action (VLA) policies using online reinforcement learning (RL) with LLM-generated rewards. Our method eliminates the need for large-scale human demonstrations or manually engineered rewards for training such agents. We benchmark against strong zero-shot baselines, including GPT-4o, and supervised fine-tuned MLLMs, on our task. Our results demonstrate that our RL-finetuned MLLM outperforms all baselines by a significant margin ($19.1$-$40.3\%$), generalizing well to novel scenes and tasks. To the best of our knowledge, this is the first demonstration of adapting MLLMs as VLA agents that can act and ask for help using LLM-generated rewards with online RL.

[Arxiv](https://arxiv.org/abs/2504.00907)