# 基于大型语言模型的程序化视频预测

发布时间：2025年05月20日

`LLM应用` `视频生成` `计算机视觉`

> Programmatic Video Prediction Using Large Language Models

# 摘要

> 估计描述真实世界过程动力学的世界模型对于预测未来结果至关重要。在视频监控、机器人应用和自动驾驶等领域，这意味着要在给定视频片段设定视觉背景的基础上，生成合理的视觉未来。为此，我们提出了ProgGen，它通过利用大型（视觉）语言模型（LLM/VLM）的归纳偏见，使用一组神经符号、人类可解释的状态（每帧一个）来表示视频的动态，从而承担视频帧预测的任务。具体来说，ProgGen利用LLM/VLM来合成程序：(i) 在给定视觉背景（即帧）的情况下估计视频的状态；(ii) 通过估计转换动态来预测未来时间步骤对应的状态；(iii) 将预测的状态渲染为视觉RGB帧。实证评估表明，我们的方法在两个具有挑战性的环境中（i) PhyWorld (ii) Cart Pole）的视频帧预测任务中优于现有技术。此外，ProgGen支持反事实推理和可解释的视频生成，证明了其在视频生成任务中的有效性和通用性。

> The task of estimating the world model describing the dynamics of a real world process assumes immense importance for anticipating and preparing for future outcomes. For applications such as video surveillance, robotics applications, autonomous driving, etc. this objective entails synthesizing plausible visual futures, given a few frames of a video to set the visual context. Towards this end, we propose ProgGen, which undertakes the task of video frame prediction by representing the dynamics of the video using a set of neuro-symbolic, human-interpretable set of states (one per frame) by leveraging the inductive biases of Large (Vision) Language Models (LLM/VLM). In particular, ProgGen utilizes LLM/VLM to synthesize programs: (i) to estimate the states of the video, given the visual context (i.e. the frames); (ii) to predict the states corresponding to future time steps by estimating the transition dynamics; (iii) to render the predicted states as visual RGB-frames. Empirical evaluations reveal that our proposed method outperforms competing techniques at the task of video frame prediction in two challenging environments: (i) PhyWorld (ii) Cart Pole. Additionally, ProgGen permits counter-factual reasoning and interpretable video generation attesting to its effectiveness and generalizability for video generation tasks.

[Arxiv](https://arxiv.org/abs/2505.14948)