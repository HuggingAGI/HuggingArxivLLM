# # JARVIS-VLA：通过大规模视觉语言模型的后训练方法，实现使用键盘和鼠标进行视觉游戏的交互体验。

发布时间：2025年03月20日

`LLM应用` `机器人学`

> JARVIS-VLA: Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse

# 摘要

> 近年来，基于动作的决策机制在开放世界环境中备受关注。视觉语言动作（VLA）模型通过大规模网络数据集的预训练，在决策任务中展现出巨大潜力。然而，以往研究主要集中在动作后训练，却忽视了对基础模型本身的优化。为此，我们提出了一种新型方法——基于视觉语言后训练的动作生成（Act from Visual Language Post-Training），该方法通过视觉和语言指导以自监督方式优化视觉语言模型（VLMs）。这种改进显著提升了模型在开放世界环境中对世界知识、视觉识别和空间定位的能力。遵循这一后训练范式，我们在Minecraft环境中首次实现了能够遵循人类指令执行超过1000种不同原子任务的VLA模型，涵盖制作、冶炼、烹饪、采矿和战斗等。实验结果表明，与最佳代理基线相比，我们在非轨迹任务上的后训练使模型在多样化原子任务上的性能提升了40%。此外，我们的方法在Minecraft中超越了传统基于模仿学习的策略，达到了目前最先进的性能水平。我们已开源代码、模型和数据集，以推动进一步研究。项目页面可在以下链接找到：https://craftjarvis.github.io/JarvisVLA。

> Recently, action-based decision-making in open-world environments has gained significant attention. Visual Language Action (VLA) models, pretrained on large-scale web datasets, have shown promise in decision-making tasks. However, previous work has primarily focused on action post-training, often neglecting enhancements to the foundational model itself. In response, we introduce a novel approach, Act from Visual Language Post-Training, which refines Visual Language Models (VLMs) through visual and linguistic guidance in a self-supervised manner. This enhancement improves the models' capabilities in world knowledge, visual recognition, and spatial grounding in open-world environments. Following the above post-training paradigms, we obtain the first VLA models in Minecraft that can follow human instructions on over 1k different atomic tasks, including crafting, smelting, cooking, mining, and killing. Our experiments demonstrate that post-training on non-trajectory tasks leads to a significant 40% improvement over the best agent baseline on a diverse set of atomic tasks. Furthermore, we demonstrate that our approach surpasses traditional imitation learning-based policies in Minecraft, achieving state-of-the-art performance. We have open-sourced the code, models, and datasets to foster further research. The project page can be found in https://craftjarvis.github.io/JarvisVLA.

[Arxiv](https://arxiv.org/abs/2503.16365)