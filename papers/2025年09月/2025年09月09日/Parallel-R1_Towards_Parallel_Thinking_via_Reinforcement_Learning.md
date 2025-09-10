# Parallel-R1：基于强化学习的并行思考探索

发布时间：2025年09月09日

`强化学习` `教育科技`

> Parallel-R1: Towards Parallel Thinking via Reinforcement Learning

# 摘要

> 并行思维作为一种新方法应运而生，它通过同时探索多条推理路径来增强大型语言模型（LLMs）的推理能力。然而，通过训练激活这些能力仍颇具挑战：现有方法主要依赖合成数据上的监督微调（SFT），这种方式更倾向于教师强制模仿，而非鼓励探索与泛化。与之不同，我们提出了	extbf{Parallel-R1}——首个能够让复杂现实推理任务实现并行思维的强化学习（RL）框架。该框架采用渐进式课程设计，专门解决了用RL训练并行思维时的冷启动难题：我们首先针对简单任务中提示生成的轨迹进行SFT，以初步培养并行思维能力；随后过渡到RL，在更复杂的问题上探索并泛化这一技能。在MATH、AMC23和AIME等多个数学基准测试上的实验表明，Parallel-R1成功培养了并行思维能力——相较于直接在复杂任务上用RL训练的顺序思维模型，其准确率提升了8.4%。进一步分析发现，模型的思维行为发生了显著转变：训练初期将并行思维用作探索策略，后期则运用这一能力进行多视角验证。最重要的是，我们验证了并行思维可作为一种	extbf{训练中期探索支架}：这一临时探索阶段在RL训练后能解锁更高的性能上限，在AIME25上较基线提升了42.9%。我们的模型、数据及代码将开源于https://github.com/zhengkid/Parallel-R1。

> Parallel thinking has emerged as a novel approach for enhancing the reasoning capabilities of large language models (LLMs) by exploring multiple reasoning paths concurrently. However, activating such capabilities through training remains challenging, as existing methods predominantly rely on supervised fine-tuning (SFT) over synthetic data, which encourages teacher-forced imitation rather than exploration and generalization. Different from them, we propose \textbf{Parallel-R1}, the first reinforcement learning (RL) framework that enables parallel thinking behaviors for complex real-world reasoning tasks. Our framework employs a progressive curriculum that explicitly addresses the cold-start problem in training parallel thinking with RL. We first use SFT on prompt-generated trajectories from easier tasks to instill the parallel thinking ability, then transition to RL to explore and generalize this skill on harder problems. Experiments on various math benchmarks, including MATH, AMC23, and AIME, show that Parallel-R1 successfully instills parallel thinking, leading to 8.4% accuracy improvements over the sequential thinking model trained directly on challenging tasks with RL. Further analysis reveals a clear shift in the model's thinking behavior: at an early stage, it uses parallel thinking as an exploration strategy, while in a later stage, it uses the same capability for multi-perspective verification. Most significantly, we validate parallel thinking as a \textbf{mid-training exploration scaffold}, where this temporary exploratory phase unlocks a higher performance ceiling after RL, yielding a 42.9% improvement over the baseline on AIME25. Our model, data, and code will be open-source at https://github.com/zhengkid/Parallel-R1.

[Arxiv](https://arxiv.org/abs/2509.07980)