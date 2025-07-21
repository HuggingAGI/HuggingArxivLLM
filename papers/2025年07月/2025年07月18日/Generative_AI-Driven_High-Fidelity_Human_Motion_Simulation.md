# 生成式AI驱动的高保真人体运动模拟

发布时间：2025年07月18日

`LLM应用` `人工智能`

> Generative AI-Driven High-Fidelity Human Motion Simulation

# 摘要

> 人类运动仿真（HMS）为评估工业任务中的工人行为、安全和生产力提供了一种经济高效的方式。然而，现有方法通常面临动作保真度较低的问题。本研究引入了生成式AI增强的人类运动仿真（G-AI-HMS），通过整合文本到文本和文本到动作模型，显著提升了物理任务的仿真质量。G-AI-HMS主要解决两个关键挑战：（1）利用与 MotionGPT 训练词汇对齐的大型语言模型，将任务描述转化为具有动作感知的语言；（2）通过计算机视觉技术，将AI增强的动作与真实人类动作进行对比验证。通过对实时视频应用姿态估计算法，提取关节关键点，并使用动作相似性指标，将其与AI增强序列进行比较。在涉及八项任务的案例研究中，AI增强的动作在大多数场景下表现出更低的误差，相较于人工创建的描述，在六项任务中基于空间准确性表现更优，在四项任务中基于姿态归一化后的对齐度表现更佳，以及在七项任务中基于整体时间相似性表现更优。统计分析表明，AI增强的提示显著降低了关节误差和时间偏移（p < 0.0001），同时保持了可比的姿态准确性。

> Human motion simulation (HMS) supports cost-effective evaluation of worker behavior, safety, and productivity in industrial tasks. However, existing methods often suffer from low motion fidelity. This study introduces Generative-AI-Enabled HMS (G-AI-HMS), which integrates text-to-text and text-to-motion models to enhance simulation quality for physical tasks. G-AI-HMS tackles two key challenges: (1) translating task descriptions into motion-aware language using Large Language Models aligned with MotionGPT's training vocabulary, and (2) validating AI-enhanced motions against real human movements using computer vision. Posture estimation algorithms are applied to real-time videos to extract joint landmarks, and motion similarity metrics are used to compare them with AI-enhanced sequences. In a case study involving eight tasks, the AI-enhanced motions showed lower error than human created descriptions in most scenarios, performing better in six tasks based on spatial accuracy, four tasks based on alignment after pose normalization, and seven tasks based on overall temporal similarity. Statistical analysis showed that AI-enhanced prompts significantly (p $<$ 0.0001) reduced joint error and temporal misalignment while retaining comparable posture accuracy.

[Arxiv](https://arxiv.org/abs/2507.14097)