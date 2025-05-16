# ImagineBench: 用大语言模型的 rollout 来评估强化学习

发布时间：2025年05月15日

`其他` `人工智能` `机器人学`

> ImagineBench: Evaluating Reinforcement Learning with Large Language Model Rollouts

# 摘要

> 强化学习 (RL) 中的核心挑战在于其对大量真实世界交互数据的依赖，用于学习特定任务的策略。尽管近期研究表明大型语言模型 (LLMs) 可以通过生成合成经验（即想象轨迹）来缓解这一限制，从而掌握新任务，但这一新兴领域的发展却因缺乏标准基准而受阻。为了解决这一问题，我们引入了 ImagineBench，这是首个全面的基准测试框架，用于评估同时利用真实轨迹和 LLM-想象轨迹的离线 RL 算法。ImagineBench 的关键特性包括：(1) 包含环境收集的真实轨迹和 LLM-想象轨迹的数据集；(2) 覆盖运动、机器人操作和导航任务的多样化环境领域；以及 (3) 提供不同复杂度级别的自然语言任务指令，以促进语言条件策略学习。通过对现有最先进的离线 RL 算法进行系统性评估，我们发现，直接应用现有的离线 RL 算法在新任务上表现不佳，仅在困难任务中达到 35.44% 的成功率，而基于真实轨迹训练的方法在困难任务中达到了 64.37% 的成功率。这一结果凸显了算法改进的必要性，以便更好地利用 LLM-想象轨迹。此外，我们还识别了未来研究的关键方向，包括更好地利用想象轨迹、快速在线适应和持续学习，以及扩展到多模态任务。我们的代码已公开发布在 https://github.com/LAMDA-RL/ImagineBench。


> A central challenge in reinforcement learning (RL) is its dependence on extensive real-world interaction data to learn task-specific policies. While recent work demonstrates that large language models (LLMs) can mitigate this limitation by generating synthetic experience (noted as imaginary rollouts) for mastering novel tasks, progress in this emerging field is hindered due to the lack of a standard benchmark. To bridge this gap, we introduce ImagineBench, the first comprehensive benchmark for evaluating offline RL algorithms that leverage both real rollouts and LLM-imaginary rollouts. The key features of ImagineBench include: (1) datasets comprising environment-collected and LLM-imaginary rollouts; (2) diverse domains of environments covering locomotion, robotic manipulation, and navigation tasks; and (3) natural language task instructions with varying complexity levels to facilitate language-conditioned policy learning. Through systematic evaluation of state-of-the-art offline RL algorithms, we observe that simply applying existing offline RL algorithms leads to suboptimal performance on unseen tasks, achieving 35.44% success rate in hard tasks in contrast to 64.37% of method training on real rollouts for hard tasks. This result highlights the need for algorithm advancements to better leverage LLM-imaginary rollouts. Additionally, we identify key opportunities for future research: including better utilization of imaginary rollouts, fast online adaptation and continual learning, and extension to multi-modal tasks. Our code is publicly available at https://github.com/LAMDA-RL/ImagineBench.

[Arxiv](https://arxiv.org/abs/2505.10010)