# 基于变分同态的选项诱导抽象马尔可夫决策过程时间抽象研究

发布时间：2025年07月22日

`LLM理论` `人工智能` `推理系统`

> Learning Temporal Abstractions via Variational Homomorphisms in Option-Induced Abstract MDPs

# 摘要

> 大型语言模型（LLMs）在显式链式思维（CoT）提示下展现了强大的推理能力，但生成分步的文本解释却成本高昂且效率低下。为此，我们提出了一种高效隐式推理框架，让模型能够在潜在空间中“思考”，无需每步生成显式文本。我们建议将这些潜在思维建模为分层强化学习框架内的时序扩展抽象动作（选项）。为学习多样化的潜在选项库，我们引入了变分马尔可夫决策过程选项评论（VMOC），这是一种基于变分推断的无策略算法。为将这些选项用作抽象推理空间，我们扩展了连续MDP同构理论，证明在简化潜在空间中学习策略（VMOC适用）可保留对原始复杂问题的最优解。最后，我们提出冷启动流程，利用监督微调（SFT）数据将人类推理演示提炼到潜在选项空间中，为模型推理能力提供丰富初始化。实验表明，我们的方法在复杂逻辑推理基准和挑战性运动任务中表现优异，证实了其作为学习语言和控制抽象技能的原理化方法的合理性。


> Large Language Models (LLMs) have shown remarkable reasoning ability through explicit Chain-of-Thought (CoT) prompting, but generating these step-by-step textual explanations is computationally expensive and slow. To overcome this, we aim to develop a framework for efficient, implicit reasoning, where the model "thinks" in a latent space without generating explicit text for every step. We propose that these latent thoughts can be modeled as temporally-extended abstract actions, or options, within a hierarchical reinforcement learning framework. To effectively learn a diverse library of options as latent embeddings, we first introduce the Variational Markovian Option Critic (VMOC), an off-policy algorithm that uses variational inference within the HiT-MDP framework. To provide a rigorous foundation for using these options as an abstract reasoning space, we extend the theory of continuous MDP homomorphisms. This proves that learning a policy in the simplified, abstract latent space, for which VMOC is suited, preserves the optimality of the solution to the original, complex problem. Finally, we propose a cold-start procedure that leverages supervised fine-tuning (SFT) data to distill human reasoning demonstrations into this latent option space, providing a rich initialization for the model's reasoning capabilities. Extensive experiments demonstrate that our approach achieves strong performance on complex logical reasoning benchmarks and challenging locomotion tasks, validating our framework as a principled method for learning abstract skills for both language and control.

[Arxiv](https://arxiv.org/abs/2507.16473)