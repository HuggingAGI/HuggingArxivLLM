# 图融合视觉-语言-动作：多臂机器人操作中的策略推理方法

发布时间：2025年09月09日

`Agent` `工业与制造`

> Graph-Fused Vision-Language-Action for Policy Reasoning in Multi-Arm Robotic Manipulation

# 摘要

> 从人类视频演示中习得机器人灵巧技能仍是一大难题，症结在于传统方法依赖低级轨迹复制，难以在不同物体、空间布局和机械臂配置间泛化。为此，我们提出图融合视觉-语言-动作（GF-VLA）统一框架，让双臂机器人系统能直接从RGB-D人类演示中完成任务级推理与执行。GF-VLA采用信息论方法提取任务关键线索，精准捕捉手-物和物-物的核心交互，将这些线索构建成时序场景图，再与语言条件Transformer融合，生成层次化行为树和可解释的笛卡尔运动原语。为提升双臂执行效率，我们设计跨臂分配策略，无需显式几何建模即可自主分配抓取器。我们在四个双臂积木组装基准任务上验证了GF-VLA，这些任务涉及符号结构构建与空间泛化。实验结果显示，该表示方法实现了超95%的图准确率和93%的子任务分割，助力语言-动作规划器生成鲁棒且可解释的任务策略。在双臂机器人上部署后，这些策略在堆叠、字母成形和几何重构任务中，抓取可靠性达94%，放置精度89%，整体任务成功率90%，充分证明了在多样空间和语义变化下的强泛化性与鲁棒性。

> Acquiring dexterous robotic skills from human video demonstrations remains a significant challenge, largely due to conventional reliance on low-level trajectory replication, which often fails to generalize across varying objects, spatial layouts, and manipulator configurations. To address this limitation, we introduce Graph-Fused Vision-Language-Action (GF-VLA), a unified framework that enables dual-arm robotic systems to perform task-level reasoning and execution directly from RGB-D human demonstrations. GF-VLA employs an information-theoretic approach to extract task-relevant cues, selectively highlighting critical hand-object and object-object interactions. These cues are structured into temporally ordered scene graphs, which are subsequently integrated with a language-conditioned transformer to produce hierarchical behavior trees and interpretable Cartesian motion primitives. To enhance efficiency in bimanual execution, we propose a cross-arm allocation strategy that autonomously determines gripper assignment without requiring explicit geometric modeling. We validate GF-VLA on four dual-arm block assembly benchmarks involving symbolic structure construction and spatial generalization. Empirical results demonstrate that the proposed representation achieves over 95% graph accuracy and 93% subtask segmentation, enabling the language-action planner to generate robust, interpretable task policies. When deployed on a dual-arm robot, these policies attain 94% grasp reliability, 89% placement accuracy, and 90% overall task success across stacking, letter-formation, and geometric reconfiguration tasks, evidencing strong generalization and robustness under diverse spatial and semantic variations.

[Arxiv](https://arxiv.org/abs/2509.07957)