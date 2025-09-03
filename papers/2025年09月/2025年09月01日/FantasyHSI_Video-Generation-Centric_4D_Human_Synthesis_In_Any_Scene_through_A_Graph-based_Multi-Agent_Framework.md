# <翻译失败>

发布时间：2025年09月01日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `媒体与娱乐`

> FantasyHSI: Video-Generation-Centric 4D Human Synthesis In Any Scene through A Graph-based Multi-Agent Framework

# 摘要

> 人机场景交互（HSI）致力于在复杂环境中生成逼真的人类行为，然而在处理长时序高级任务及泛化到未见场景时仍面临巨大挑战。为克服这些局限，我们提出了FantasyHSI——一个无需配对数据、以视频生成和多智能体系统为核心的新型HSI框架。我们将这一复杂交互过程建模为动态有向图，并基于此构建了协作式多智能体系统。该系统包含两个核心智能体：负责环境感知与高级路径规划的场景导航智能体，以及将长时序目标分解为原子动作的规划智能体。尤为关键的是，我们引入了评论家智能体，通过评估生成动作与规划路径的偏差构建闭环反馈机制，从而动态修正生成模型随机性导致的轨迹漂移，确保长期逻辑一致性。为提升生成动作的物理真实性，我们采用直接偏好优化（DPO）训练动作生成器，大幅减少肢体扭曲、脚部滑动等伪影问题。在我们自定义的SceneBench基准测试中，大量实验结果表明，FantasyHSI在泛化能力、长时序任务完成度及物理真实性上均显著超越现有方法。项目页面：https://fantasy-amap.github.io/fantasy-hsi/

> Human-Scene Interaction (HSI) seeks to generate realistic human behaviors within complex environments, yet it faces significant challenges in handling long-horizon, high-level tasks and generalizing to unseen scenes. To address these limitations, we introduce FantasyHSI, a novel HSI framework centered on video generation and multi-agent systems that operates without paired data. We model the complex interaction process as a dynamic directed graph, upon which we build a collaborative multi-agent system. This system comprises a scene navigator agent for environmental perception and high-level path planning, and a planning agent that decomposes long-horizon goals into atomic actions. Critically, we introduce a critic agent that establishes a closed-loop feedback mechanism by evaluating the deviation between generated actions and the planned path. This allows for the dynamic correction of trajectory drifts caused by the stochasticity of the generative model, thereby ensuring long-term logical consistency. To enhance the physical realism of the generated motions, we leverage Direct Preference Optimization (DPO) to train the action generator, significantly reducing artifacts such as limb distortion and foot-sliding. Extensive experiments on our custom SceneBench benchmark demonstrate that FantasyHSI significantly outperforms existing methods in terms of generalization, long-horizon task completion, and physical realism. Ours project page: https://fantasy-amap.github.io/fantasy-hsi/

[Arxiv](https://arxiv.org/abs/2509.01232)