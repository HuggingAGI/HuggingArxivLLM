# 自我适应型语言模型

发布时间：2025年06月12日

`LLM理论` `人工智能`

> Self-Adapting Language Models

# 摘要

> 大型语言模型（LLMs）功能强大但静态，缺乏根据新任务、知识或示例调整自身权重的机制。我们推出自我适应的大型语言模型（SEAL），这是一个使LLMs能够实现自我适应的创新框架。通过自动生成微调数据和更新指令，SEAL赋予模型自我进化的能力。当面对新的输入时，模型会进行自我编辑——以不同方式重组信息、指定优化超参数或调用数据增强和基于梯度更新工具。通过监督微调（SFT），这些自我编辑会触发持久的权重更新，从而实现持续的适应。为了训练模型生成有效的自我编辑，我们采用了一个强化学习循环，其中更新后模型的下游性能作为奖励信号。与依赖独立适应模块或辅助网络的传统方法不同，SEAL直接利用模型自身的生成内容来控制其适应过程。在知识整合和少量样本泛化方面的实验表明，SEAL是迈向能够自我主导适应的语言模型的重要一步。更多详情请访问我们的网站和代码：https://jyopari.github.io/posts/seal。

> Large language models (LLMs) are powerful but static; they lack mechanisms to adapt their weights in response to new tasks, knowledge, or examples. We introduce Self-Adapting LLMs (SEAL), a framework that enables LLMs to self-adapt by generating their own finetuning data and update directives. Given a new input, the model produces a self-edit-a generation that may restructure the information in different ways, specify optimization hyperparameters, or invoke tools for data augmentation and gradient-based updates. Through supervised finetuning (SFT), these self-edits result in persistent weight updates, enabling lasting adaptation. To train the model to produce effective self-edits, we use a reinforcement learning loop with the downstream performance of the updated model as the reward signal. Unlike prior approaches that rely on separate adaptation modules or auxiliary networks, SEAL directly uses the model's own generation to control its adaptation process. Experiments on knowledge incorporation and few-shot generalization show that SEAL is a promising step toward language models capable of self-directed adaptation. Our website and code is available at https://jyopari.github.io/posts/seal.

[Arxiv](https://arxiv.org/abs/2506.10943)