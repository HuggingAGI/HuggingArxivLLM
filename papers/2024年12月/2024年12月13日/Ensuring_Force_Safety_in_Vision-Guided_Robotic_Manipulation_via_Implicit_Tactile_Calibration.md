# 借助隐式触觉校准保障视觉引导机器人操作时的力安全

发布时间：2024年12月13日

`Agent` `机器人` `触觉感知`

> Ensuring Force Safety in Vision-Guided Robotic Manipulation via Implicit Tactile Calibration

# 摘要

> 在动态环境里，机器人操作像门这类具有特定属性的物体时，常常遭遇受限的运动轨迹。所以，施加恰当的力对避免机器人和物体受损极为关键。但当下的视觉引导机器人状态生成方法在这方面常不尽人意，原因是缺少触觉感知的融合。为应对此难题，本文推出了一个新颖的状态扩散框架，叫做 SafeDiff。它能依据当前机器人状态和视觉上下文观察生成预期状态序列，同时结合实时触觉反馈来完善该序列。据了解，这是首个专门致力于保障机器人操作中的力安全的研究。它极大地提升了状态规划的合理性，且基于此优化规划通过逆动力学得出安全动作轨迹。实际上，和以往将视觉与触觉数据拼接以生成未来机器人状态序列的方法不同，我们的方法把触觉数据当作校准信号，在状态空间内隐性地调整机器人的状态。另外，我们还构建了一个大规模的模拟数据集，名为 SafeDoorManip50k，提供了丰富的多模态数据来训练和评估所提方法。大量实验表明，我们的视觉-触觉模型在模拟和真实场景中，都显著降低了开门时有害力的风险。

> In dynamic environments, robots often encounter constrained movement trajectories when manipulating objects with specific properties, such as doors. Therefore, applying the appropriate force is crucial to prevent damage to both the robots and the objects. However, current vision-guided robot state generation methods often falter in this regard, as they lack the integration of tactile perception. To tackle this issue, this paper introduces a novel state diffusion framework termed SafeDiff. It generates a prospective state sequence from the current robot state and visual context observation while incorporating real-time tactile feedback to refine the sequence. As far as we know, this is the first study specifically focused on ensuring force safety in robotic manipulation. It significantly enhances the rationality of state planning, and the safe action trajectory is derived from inverse dynamics based on this refined planning. In practice, unlike previous approaches that concatenate visual and tactile data to generate future robot state sequences, our method employs tactile data as a calibration signal to adjust the robot's state within the state space implicitly. Additionally, we've developed a large-scale simulation dataset called SafeDoorManip50k, offering extensive multimodal data to train and evaluate the proposed method. Extensive experiments show that our visual-tactile model substantially mitigates the risk of harmful forces in the door opening, across both simulated and real-world settings.

[Arxiv](https://arxiv.org/abs/2412.10349)