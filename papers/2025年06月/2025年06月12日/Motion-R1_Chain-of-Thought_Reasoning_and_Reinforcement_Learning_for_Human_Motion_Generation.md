# Motion-R1：通过链式推理与强化学习实现人类动作生成

发布时间：2025年06月12日

`LLM应用

摘要中的论文探讨了大型语言模型在文本到动作生成中的应用，提出了一种新的框架来改进动作生成的质量和多样性。这属于LLM的应用层面，因此归类为LLM应用。` `机器人` `动作生成`

> Motion-R1: Chain-of-Thought Reasoning and Reinforcement Learning for Human Motion Generation

# 摘要

> 大型语言模型在自然语言理解和推理方面的突破为文本到动作生成带来了新的可能性。现有方法虽在语义对齐和动作合成上取得进展，但受限于端到端映射策略，难以捕捉深层语言结构和逻辑推理。因此，生成动作常缺乏可控性、一致性和多样性。为解决这一问题，我们提出Motion-R1，一个集成了链式思维机制的统一动作-语言建模框架。通过将复杂文本指令分解为逻辑结构化动作路径，Motion-R1为动作生成提供高层次语义指导，显著提升模型对多步骤、长时域和语义丰富命令的解释与执行能力。为训练模型，我们采用针对大型模型设计的强化学习算法——Group Relative Policy Optimization，该算法利用动作质量反馈联合优化推理链和动作合成。在多个基准数据集上的实验表明，Motion-R1在需要细腻语义理解和长期时间连贯性的情景下，表现优于现有最优方法。代码、模型和数据将公开发布。

> Recent advances in large language models, especially in natural language understanding and reasoning, have opened new possibilities for text-to-motion generation. Although existing approaches have made notable progress in semantic alignment and motion synthesis, they often rely on end-to-end mapping strategies that fail to capture deep linguistic structures and logical reasoning. Consequently, generated motions tend to lack controllability, consistency, and diversity. To address these limitations, we propose Motion-R1, a unified motion-language modeling framework that integrates a Chain-of-Thought mechanism. By explicitly decomposing complex textual instructions into logically structured action paths, Motion-R1 provides high-level semantic guidance for motion generation, significantly enhancing the model's ability to interpret and execute multi-step, long-horizon, and compositionally rich commands. To train our model, we adopt Group Relative Policy Optimization, a reinforcement learning algorithm designed for large models, which leverages motion quality feedback to optimize reasoning chains and motion synthesis jointly. Extensive experiments across multiple benchmark datasets demonstrate that Motion-R1 achieves competitive or superior performance compared to state-of-the-art methods, particularly in scenarios requiring nuanced semantic understanding and long-term temporal coherence. The code, model and data will be publicly available.

[Arxiv](https://arxiv.org/abs/2506.10353)