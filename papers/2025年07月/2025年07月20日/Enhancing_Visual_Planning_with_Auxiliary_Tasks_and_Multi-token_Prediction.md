# # 通过辅助任务与多标记预测提升视觉规划能力

发布时间：2025年07月20日

`LLM应用` `计算机视觉` `人工智能`

> Enhancing Visual Planning with Auxiliary Tasks and Multi-token Prediction

# 摘要

> 视觉辅助规划（VPA）的目标是根据用户进展视频，预测实现特定目标所需的动作序列。尽管多模态大型语言模型（MLLMs）在视频理解方面取得了显著进展，但长期视觉规划仍具挑战性。我们识别出两个主要挑战：程序标注稀缺性和传统预测目标的局限性。为了解决数据稀缺问题，我们引入辅助任务增强，通过训练模型在相关辅助任务上学习，提升规划能力。同时，我们采用多词预测扩展传统方法，更有效地建模结构化动作空间。我们的VideoPlan方法在COIN和CrossTask数据集上取得最优性能，并成功扩展至Ego4D任务，展示了强大的通用性。代码即将公开。

> Visual Planning for Assistance (VPA) aims to predict a sequence of user actions required to achieve a specified goal based on a video showing the user's progress. Although recent advances in multimodal large language models (MLLMs) have shown promising results in video understanding, long-horizon visual planning remains a challenging problem. We identify two challenges in training large MLLMs for video-based planning tasks: (1) scarcity of procedural annotations, limiting the model's ability to learn procedural task dynamics effectively, and (2) inefficiency of next-token prediction objective to explicitly capture the structured action space for visual planning when compared to free-form, natural language. To tackle data scarcity, we introduce Auxiliary Task Augmentation. We design and train our model on auxiliary tasks relevant to long-horizon video-based planning (e.g., goal prediction) to augment the model's planning ability. To more explicitly model the structured action space unique to visual planning tasks, we leverage Multi-token Prediction, extending traditional next-token prediction by using multiple heads to predict multiple future tokens during training. Our approach, VideoPlan, achieves state-of-the-art VPA performance on the COIN and CrossTask datasets, surpassing prior methods by 7.3% and 3.4%, respectively, when predicting 3 future actions. We further extend our method to the challenging Ego4D Long-term Action Anticipation task, and show that it is on par with the state-of-the-art approaches despite not using specialized egocentric features. Code will be made available.

[Arxiv](https://arxiv.org/abs/2507.15130)