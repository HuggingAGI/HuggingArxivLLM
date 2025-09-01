# 模拟物理学家的眼光：一种以VLM为核心的物理公式发现方法

发布时间：2025年08月24日

`Agent` `基础理论`

> Mimicking the Physicist's Eye:A VLM-centric Approach for Physics Formula Discovery

# 摘要

> 在人工智能领域，从现实世界观测数据中自动发现物理定律一直是一项重大挑战。当前方法多依赖符号回归或大型语言模型（LLMs），但它们局限于单模态数据，忽略了物理学家眼中至关重要的运动视觉现象——这些丰富表征对物理研究不可或缺。这种“感官缺失”严重削弱了模型对动态现象内在时空模式的解读能力。

为此，我们提出多模态模型VIPER-R1，它通过基于物理的方程推理视觉归纳（Visual Induction for Physics-based Equation Reasoning）来发现基本符号公式。该模型融合视觉感知、轨迹数据与符号推理，模拟科学发现的完整过程。

模型训练采用运动结构归纳（MSI）课程：先通过监督微调解析运动学相图，在因果思维链（C-CoT）引导下生成假设；再通过奖励引导符号校准（RGSC），结合强化学习优化公式结构。推理阶段，训练后的VIPER-R1化身“物理智能体”：先提出高置信度的符号近似解，再主动调用外部符号回归工具进行符号残差对齐（SR²）。这一步恰似物理学家的微扰分析，让理论模型与经验数据达成完美契合。

为支持研究，我们还构建了包含5000个实例的新型多模态语料库PhysSymbol。实验结果显示，VIPER-R1在准确性和可解释性上均持续超越现有最优视觉语言模型（VLM）基线，为物理定律的精准发现提供了更强能力。

项目页面：https://jiaaqiliu.github.io/VIPER-R1/

> Automated discovery of physical laws from observational data in the real world is a grand challenge in AI. Current methods, relying on symbolic regression or LLMs, are limited to uni-modal data and overlook the rich, visual phenomenological representations of motion that are indispensable to physicists. This "sensory deprivation" severely weakens their ability to interpret the inherent spatio-temporal patterns within dynamic phenomena. To address this gap, we propose VIPER-R1, a multimodal model that performs Visual Induction for Physics-based Equation Reasoning to discover fundamental symbolic formulas. It integrates visual perception, trajectory data, and symbolic reasoning to emulate the scientific discovery process. The model is trained via a curriculum of Motion Structure Induction (MSI), using supervised fine-tuning to interpret kinematic phase portraits and to construct hypotheses guided by a Causal Chain of Thought (C-CoT), followed by Reward-Guided Symbolic Calibration (RGSC) to refine the formula structure with reinforcement learning. During inference, the trained VIPER-R1 acts as an agent: it first posits a high-confidence symbolic ansatz, then proactively invokes an external symbolic regression tool to perform Symbolic Residual Realignment (SR^2). This final step, analogous to a physicist's perturbation analysis, reconciles the theoretical model with empirical data. To support this research, we introduce PhysSymbol, a new 5,000-instance multimodal corpus. Experiments show that VIPER-R1 consistently outperforms state-of-the-art VLM baselines in accuracy and interpretability, enabling more precise discovery of physical laws. Project page: https://jiaaqiliu.github.io/VIPER-R1/

[Arxiv](https://arxiv.org/abs/2508.17380)