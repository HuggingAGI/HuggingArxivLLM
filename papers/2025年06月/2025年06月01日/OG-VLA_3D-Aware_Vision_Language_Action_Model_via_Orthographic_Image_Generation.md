# OG-VLA：基于正交图像生成的3D感知视觉语言动作模型

发布时间：2025年06月01日

`Agent

理由：这篇论文专注于结合视觉语言动作模型（VLAs）和3D感知策略来构建一个机器人智能体（Agent），使其能够根据自然语言指令执行动作。虽然使用了大型语言模型（LLM），但论文的核心在于智能体的架构和应用，属于智能体领域。` `机器人技术` `计算机视觉`

> OG-VLA: 3D-Aware Vision Language Action Model via Orthographic Image Generation

# 摘要

> 我们推出OG-VLA，一种结合视觉语言动作模型（VLAs）泛化优势与3D感知策略稳健性的全新架构与学习框架。OG-VLA旨在解决将自然语言指令与多视图RGBD观测结果转化为准静态机器人动作的难题。当前，3D感知策略在精准机器人操作任务中表现卓越，但面对新指令、场景和物体时，其泛化能力仍有待提升。而VLAs虽在跨指令与跨场景泛化上表现优异，却对摄像头与机器人姿态的变化较为敏感。我们通过整合语言与视觉基础模型中的先验知识，显著提升了3D感知关键帧策略的泛化性能。OG-VLA将多视角输入观测数据映射至点云，并通过规范正交视图进行渲染，确保输入视角的一致性与输入输出空间的统一。这些规范视图经由视觉主干网络、大型语言模型（LLM）与图像扩散模型处理，生成编码末端执行器在输入场景中下一位置与姿态的图像。在Arnold和Colosseum基准测试中，OG-VLA在未见过的环境中展现出目前最优的泛化能力，同时在已见过的场景中保持了稳健性能，相对提升超过40%。此外，我们还展示了其在3到5次演示中的实际应用适应性与强大的泛化能力。更多视频与资源，请访问https://og-vla.github.io/

> We introduce OG-VLA, a novel architecture and learning framework that combines the generalization strengths of Vision Language Action models (VLAs) with the robustness of 3D-aware policies. We address the challenge of mapping natural language instructions and multi-view RGBD observations to quasi-static robot actions. 3D-aware robot policies achieve state-of-the-art performance on precise robot manipulation tasks, but struggle with generalization to unseen instructions, scenes, and objects. On the other hand, VLAs excel at generalizing across instructions and scenes, but can be sensitive to camera and robot pose variations. We leverage prior knowledge embedded in language and vision foundation models to improve generalization of 3D-aware keyframe policies. OG-VLA projects input observations from diverse views into a point cloud which is then rendered from canonical orthographic views, ensuring input view invariance and consistency between input and output spaces. These canonical views are processed with a vision backbone, a Large Language Model (LLM), and an image diffusion model to generate images that encode the next position and orientation of the end-effector on the input scene. Evaluations on the Arnold and Colosseum benchmarks demonstrate state-of-the-art generalization to unseen environments, with over 40% relative improvements while maintaining robust performance in seen settings. We also show real-world adaption in 3 to 5 demonstrations along with strong generalization. Videos and resources at https://og-vla.github.io/

[Arxiv](https://arxiv.org/abs/2506.01196)