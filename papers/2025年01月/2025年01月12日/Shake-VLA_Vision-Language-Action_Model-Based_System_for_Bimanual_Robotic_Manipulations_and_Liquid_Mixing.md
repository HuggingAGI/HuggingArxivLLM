# Shake-VLA: 基于视觉-语言-动作模型的双手机器人操作与液体混合系统

发布时间：2025年01月12日

`Agent

理由：这篇论文描述了一个基于视觉-语言-动作（VLA）模型的系统，专为双手机器人操作设计，用于自动化鸡尾酒制备。该系统集成了多个模块，包括视觉模块、语音转文本模块、语言模型、力扭矩传感器、检索增强生成（RAG）模块、异常检测机制和双手机器人手臂。这些模块协同工作，使机器人能够执行复杂的任务，如检测配料、解析用户指令、生成任务特定的机器人指令、精确测量液体量、访问和调整配方、识别异常并进行灵巧操作。这种系统符合“Agent”的定义，即一个能够感知环境、处理信息并采取行动以实现特定目标的自主实体。` `食品饮料` `机器人`

> Shake-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Manipulations and Liquid Mixing

# 摘要

> 本文介绍了Shake-VLA，一个基于视觉-语言-动作（VLA）模型的系统，专为双手机器人操作设计，用于自动化鸡尾酒制备。该系统集成了视觉模块检测配料瓶和读取标签，语音转文本模块解析用户指令，以及语言模型生成任务特定的机器人指令。力扭矩（FT）传感器精确测量倒出的液体量，确保混合过程中配料比例的准确性。系统架构包括检索增强生成（RAG）模块访问和调整配方，异常检测机制解决配料可用性问题，以及双手机器人手臂进行灵巧操作。实验评估显示，系统组件表现优异：语音转文本模块在嘈杂环境中成功率达93%，视觉模块在杂乱环境中物体和标签检测成功率达91%，异常模块成功识别95%的配料与配方差异，系统在从配方制定到动作生成的整个鸡尾酒制备过程中实现了100%的总体成功率。

> This paper introduces Shake-VLA, a Vision-Language-Action (VLA) model-based system designed to enable bimanual robotic manipulation for automated cocktail preparation. The system integrates a vision module for detecting ingredient bottles and reading labels, a speech-to-text module for interpreting user commands, and a language model to generate task-specific robotic instructions. Force Torque (FT) sensors are employed to precisely measure the quantity of liquid poured, ensuring accuracy in ingredient proportions during the mixing process. The system architecture includes a Retrieval-Augmented Generation (RAG) module for accessing and adapting recipes, an anomaly detection mechanism to address ingredient availability issues, and bimanual robotic arms for dexterous manipulation. Experimental evaluations demonstrated a high success rate across system components, with the speech-to-text module achieving a 93% success rate in noisy environments, the vision module attaining a 91% success rate in object and label detection in cluttered environment, the anomaly module successfully identified 95% of discrepancies between detected ingredients and recipe requirements, and the system achieved an overall success rate of 100% in preparing cocktails, from recipe formulation to action generation.

[Arxiv](https://arxiv.org/abs/2501.06919)