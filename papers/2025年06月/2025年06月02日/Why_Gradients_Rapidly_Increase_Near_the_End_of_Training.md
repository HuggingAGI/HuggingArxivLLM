# # 训练末期梯度为何急剧上升

发布时间：2025年06月02日

`LLM理论` `机器学习`

> Why Gradients Rapidly Increase Near the End of Training

# 摘要

> 在长期训练大型语言模型 (LLM) 时，我们观察到梯度范数在训练末期迅速上升。经过研究，我们发现这一现象源于权重衰减、归一化层与学习率调度之间的意外交互。针对这一问题，我们提出了一种简单有效的修正方法，不仅解决了梯度范数上升的问题，还带来了更优的训练效果。

> During long-duration Large Language Model (LLM) training runs the gradient norm increases rapidly near the end of training. In this short note, we show that this increase is due to an unintended interaction between weight decay, normalization layers, and the learning rate schedule. We propose a simple correction that fixes this behavior while also resulting in lower loss values throughout training.

[Arxiv](https://arxiv.org/abs/2506.02285)