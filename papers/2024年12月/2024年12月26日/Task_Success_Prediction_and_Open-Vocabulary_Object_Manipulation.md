# 任务成功预测与开放词汇对象操作

发布时间：2024年12月26日

`Agent

理由：这篇论文的研究内容涉及预测开放词汇物体操作的未来成败，模型需要根据自然语言指令、操作前的自我中心视角图像及给定的末端执行器轨迹进行预测。这涉及到智能体（Agent）在执行任务时的决策和预测能力，特别是通过自然语言指令和视觉信息来指导操作。因此，这篇论文应归类为Agent。` `机器人`

> Task Success Prediction and Open-Vocabulary Object Manipulation

# 摘要

> 本研究专注于预测开放词汇物体操作的未来成败。模型需根据自然语言指令、操作前的自我中心视角图像及给定的末端执行器轨迹进行预测。传统方法通常在操作完成后才进行成功预测，这限制了任务序列的执行效率。我们提出了一种新方法，通过将轨迹和图像与自然语言指令对齐，提前预测操作结果。我们引入了轨迹编码器，对输入轨迹进行可学习的加权，使模型能够考虑时间动态及物体与末端执行器的交互，从而提升预测准确性。我们基于RT-1数据集构建了评估数据集，实验结果显示，我们的方法在预测准确率上优于基线方法。

> This study addresses a task designed to predict the future success or failure of open-vocabulary object manipulation. In this task, the model is required to make predictions based on natural language instructions, egocentric view images before manipulation, and the given end-effector trajectories. Conventional methods typically perform success prediction only after the manipulation is executed, limiting their efficiency in executing the entire task sequence. We propose a novel approach that enables the prediction of success or failure by aligning the given trajectories and images with natural language instructions. We introduce Trajectory Encoder to apply learnable weighting to the input trajectories, allowing the model to consider temporal dynamics and interactions between objects and the end effector, improving the model's ability to predict manipulation outcomes accurately. We constructed a dataset based on the RT-1 dataset, a large-scale benchmark for open-vocabulary object manipulation tasks, to evaluate our method. The experimental results show that our method achieved a higher prediction accuracy than baseline approaches.

[Arxiv](https://arxiv.org/abs/2412.19112)