# 利用基础模型的零-shot 标注技术扩展机器人策略学习

发布时间：2024年10月23日

`Agent

理由：这篇论文主要讨论了如何利用自然语言处理技术（如视觉-语言基础模型）来自动标注机器人数据集，从而帮助机器人更好地理解和执行自然语言指令。这涉及到将语言与感知和动作关联，属于智能体（Agent）领域的研究，特别是与机器人任务执行和自然语言理解相关的智能体应用。` `机器人`

> Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models

# 摘要

> 开发能够将人类语言与感知和动作关联的机器人面临一个核心挑战：多样化机器人数据集中自然语言注释的稀缺。此外，遵循自然语言指令的机器人策略通常依赖模板化语言或昂贵的人工标注指令进行训练，限制了其可扩展性。为此，我们推出了NILS：可扩展的自然语言指令标注系统。NILS以零-shot方式自动大规模标注未经整理的长期机器人数据，无需人工干预。它结合了预训练的视觉-语言基础模型，用于检测场景中的物体、识别物体变化、从未标注的交互数据集中分割任务，并最终标注行为数据集。在BridgeV2、Fractal和厨房游戏数据集上的评估显示，NILS能够自主标注未标注和非结构化数据集中的多样化机器人演示，同时解决了众包人工标注的诸多问题，如数据质量和多样性不足。我们使用NILS标注了从430小时机器人数据中提取的115k条轨迹，并在我们的网站上开源了自动标注代码和生成的注释：http://robottasklabeling.github.io。

> A central challenge towards developing robots that can relate human language to their perception and actions is the scarcity of natural language annotations in diverse robot datasets. Moreover, robot policies that follow natural language instructions are typically trained on either templated language or expensive human-labeled instructions, hindering their scalability. To this end, we introduce NILS: Natural language Instruction Labeling for Scalability. NILS automatically labels uncurated, long-horizon robot data at scale in a zero-shot manner without any human intervention. NILS combines pretrained vision-language foundation models in order to detect objects in a scene, detect object-centric changes, segment tasks from large datasets of unlabelled interaction data and ultimately label behavior datasets. Evaluations on BridgeV2, Fractal, and a kitchen play dataset show that NILS can autonomously annotate diverse robot demonstrations of unlabeled and unstructured datasets while alleviating several shortcomings of crowdsourced human annotations, such as low data quality and diversity. We use NILS to label over 115k trajectories obtained from over 430 hours of robot data. We open-source our auto-labeling code and generated annotations on our website: http://robottasklabeling.github.io.

[Arxiv](https://arxiv.org/abs/2410.17772)