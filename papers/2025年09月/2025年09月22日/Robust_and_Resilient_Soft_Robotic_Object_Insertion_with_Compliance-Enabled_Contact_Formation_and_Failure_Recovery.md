# 鲁棒韧性的软体机器人物体插入：通过柔顺性驱动接触形成与故障恢复

发布时间：2025年09月22日

`Agent` `工业与制造`

> Robust and Resilient Soft Robotic Object Insertion with Compliance-Enabled Contact Formation and Failure Recovery

# 摘要

> 物体插入任务在姿态不确定和环境变化时极易失败，传统上需通过手动微调或重新训练控制器解决。为此，我们提出一种全新的鲁棒弹性物体插入方法——采用被动柔顺软手腕，借助其大变形特性实现安全接触缓冲，且无需高频控制或力传感。该方法将插入过程构建为“柔顺驱动接触形态”——通过顺序接触状态逐步约束自由度，并集成自动故障恢复策略。核心创新点在于，手腕柔顺性可实现安全的重复恢复尝试——我们将此机制命名为“柔顺驱动故障恢复”。我们引入预训练视觉语言模型（VLM），通过终端姿态与图像评估每次技能执行效果，识别故障模式，并通过选择技能和更新目标生成恢复动作。仿真结果显示，该方法成功率达83%，可从多种随机干扰导致的故障中恢复，包括：抓取错位达5度、孔位误差达20mm、摩擦力增至5倍，以及面对从未见过的方形/矩形销钉；我们还在真实机器人上验证了该方法的有效性。

> Object insertion tasks are prone to failures under pose uncertainties and environmental variations, traditionally requiring manual finetuning or controller retraining. We present a novel approach for robust and resilient object insertion using a passively compliant soft wrist that enables safe contact absorption through large deformations, without high-frequency control or force sensing. Our method structures insertion as compliance-enabled contact formations, sequential contact states that progressively constrain degrees of freedom, and integrates automated failure recovery strategies. Our key insight is that wrist compliance permits safe, repeated recovery attempts; hence, we refer to it as compliance-enabled failure recovery. We employ a pre-trained vision-language model (VLM) that assesses each skill execution from terminal poses and images, identifies failure modes, and proposes recovery actions by selecting skills and updating goals. In simulation, our method achieved an 83% success rate, recovering from failures induced by randomized conditions--including grasp misalignments up to 5 degrees, hole-pose errors up to 20mm, fivefold increases in friction, and previously unseen square/rectangular pegs--and we further validate the approach on a real robot.

[Arxiv](https://arxiv.org/abs/2509.17666)