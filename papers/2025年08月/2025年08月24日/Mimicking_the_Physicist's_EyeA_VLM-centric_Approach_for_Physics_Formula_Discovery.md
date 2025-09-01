# 模拟物理学家的视角：以VLM为核心的物理公式发现方法

发布时间：2025年08月24日

`Agent` `基础理论`

> Mimicking the Physicist's Eye:A VLM-centric Approach for Physics Formula Discovery

# 摘要

> 在人工智能领域，从现实世界观测数据中自动发现物理定律一直是一项重大挑战。当前方法多依赖符号回归或大型语言模型（LLMs），却局限于单模态数据，忽略了物理学家研究中不可或缺的视觉现象学运动表示——这种“感官剥夺”严重削弱了它们对动态现象中固有时空模式的解释能力。为此，我们提出多模态模型VIPER-R1，通过基于物理的方程推理视觉归纳（Visual Induction for Physics-based Equation Reasoning）来发现基本符号公式。该模型整合视觉感知、轨迹数据与符号推理，完美模拟科学发现过程。其训练采用运动结构归纳（MSI）课程：先通过监督微调解析运动学相图，构建由因果思维链（C-CoT）引导的假设，再借助奖励引导符号校准（RGSC），利用强化学习优化公式结构。推理阶段，训练后的VIPER-R1化身智能体：先提出高置信度符号近似式，再主动调用外部符号回归工具执行符号残差重对齐（SR²）。这最后一步类似物理学家的微扰分析，实现了理论模型与经验数据的精准契合。为支持研究，我们构建了PhysSymbol——一个包含5000个实例的新型多模态语料库。实验证实，VIPER-R1在准确性和可解释性上均持续超越最先进的视觉语言模型（VLM）基线，助力更精确的物理定律发现。项目页面：https://jiaaqiliu.github.io/VIPER-R1/

> Automated discovery of physical laws from observational data in the real world is a grand challenge in AI. Current methods, relying on symbolic regression or LLMs, are limited to uni-modal data and overlook the rich, visual phenomenological representations of motion that are indispensable to physicists. This "sensory deprivation" severely weakens their ability to interpret the inherent spatio-temporal patterns within dynamic phenomena. To address this gap, we propose VIPER-R1, a multimodal model that performs Visual Induction for Physics-based Equation Reasoning to discover fundamental symbolic formulas. It integrates visual perception, trajectory data, and symbolic reasoning to emulate the scientific discovery process. The model is trained via a curriculum of Motion Structure Induction (MSI), using supervised fine-tuning to interpret kinematic phase portraits and to construct hypotheses guided by a Causal Chain of Thought (C-CoT), followed by Reward-Guided Symbolic Calibration (RGSC) to refine the formula structure with reinforcement learning. During inference, the trained VIPER-R1 acts as an agent: it first posits a high-confidence symbolic ansatz, then proactively invokes an external symbolic regression tool to perform Symbolic Residual Realignment (SR^2). This final step, analogous to a physicist's perturbation analysis, reconciles the theoretical model with empirical data. To support this research, we introduce PhysSymbol, a new 5,000-instance multimodal corpus. Experiments show that VIPER-R1 consistently outperforms state-of-the-art VLM baselines in accuracy and interpretability, enabling more precise discovery of physical laws. Project page: https://jiaaqiliu.github.io/VIPER-R1/

[Arxiv](https://arxiv.org/abs/2508.17380)