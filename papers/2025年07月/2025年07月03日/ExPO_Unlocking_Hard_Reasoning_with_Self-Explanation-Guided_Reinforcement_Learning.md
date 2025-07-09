# ExPO：利用自我解释引导的强化学习，释放复杂推理潜能

发布时间：2025年07月03日

`LLM理论` `学术研究`

> ExPO: Unlocking Hard Reasoning with Self-Explanation-Guided Reinforcement Learning

# 摘要

> 大型语言模型的突破主要归功于强化学习（RL）风格的后训练方法，这种方法通过优化模型输出来提升推理能力。GRPO风格方法使用基于结果验证器标记的自生成样本实现这一目标。然而，这些方法严重依赖模型初始生成正面样本的能力，主要优化模型已知的知识，而非解决其最初无法解决的问题。这一限制在早期强化学习训练和复杂推理任务中尤为突出，因为正面样本的生成可能性较低。为了在这些情况下解锁推理能力，模型必须探索超出当前输出分布的新推理轨迹，这需要访问足够好的正面样本以指导学习。虽然专家演示看似是一个自然的解决方案，但我们发现它们在强化学习后训练中往往效果不佳。相反，我们发现有效的正面样本应具备两个关键特性：它们应在当前策略下具有较高的可能性，并且应增加模型预测正确答案的可能性。基于这些见解，我们提出了$	extbf{自我解释策略优化（ExPO）}$——一个简单且模块化的框架，通过基于真实答案的条件生成此类样本。ExPO实现了高效的探索，引导模型生成比专家编写的CoTs更符合其策略的推理轨迹，同时确保比自身（错误的）样本更高的质量。实验表明，ExPO在推理基准上的学习效率和最终性能均有所提升，并在模型最初最困难的挑战性设置（如MATH级别5）中超越了基于专家演示的方法。


> Recent advances in large language models have been driven by reinforcement learning (RL)-style post-training, which improves reasoning by optimizing model outputs based on reward or preference signals. GRPO-style approaches implement this by using self-generated samples labeled by an outcome-based verifier. However, these methods depend heavily on the model's initial ability to produce positive samples. They primarily refine what the model already knows (distribution sharpening) rather than enabling the model to solve problems where it initially fails. This limitation is especially problematic in early-stage RL training and on challenging reasoning tasks, where positive samples are unlikely to be generated. To unlock reasoning ability in such settings, the model must explore new reasoning trajectories beyond its current output distribution. Such exploration requires access to sufficiently good positive samples to guide the learning. While expert demonstrations seem like a natural solution, we find that they are often ineffective in RL post-training. Instead, we identify two key properties of effective positive samples: they should (1) be likely under the current policy, and (2) increase the model's likelihood of predicting the correct answer. Based on these insights, we propose $\textbf{Self-Explanation Policy Optimization (ExPO)}$-a simple and modular framework that generates such samples by conditioning on the ground-truth answer. ExPO enables efficient exploration and guides the model to produce reasoning trajectories more aligned with its policy than expert-written CoTs, while ensuring higher quality than its own (incorrect) samples. Experiments show that ExPO improves both learning efficiency and final performance on reasoning benchmarks, surpassing expert-demonstration-based methods in challenging settings such as MATH level-5, where the model initially struggles the most.

[Arxiv](https://arxiv.org/abs/2507.02834)