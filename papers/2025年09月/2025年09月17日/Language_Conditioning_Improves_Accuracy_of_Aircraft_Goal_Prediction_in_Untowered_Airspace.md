# 语言调节提升无塔台空域航空器目标预测准确性

发布时间：2025年09月17日

`Agent` `交通运输`

> Language Conditioning Improves Accuracy of Aircraft Goal Prediction in Untowered Airspace

# 摘要

> 自主飞行器需在无塔台空域安全运行，而该空域的协调依赖于人类飞行员间的语音通信。安全运行需要飞行器预测其他飞行器的意图及其对应的目标位置。本文提出了一种飞行器目标预测的多模态框架，该框架融合自然语言理解与空间推理，以提升此类环境下的自主决策能力。我们借助自动语音识别和大型语言模型，转录并解读飞行员的无线电通话，识别飞行器身份，并提取离散的意图标签。这些意图标签与观测轨迹相融合，用于约束时间卷积网络和高斯混合模型，实现概率性目标预测。与仅依赖运动历史的基线方法相比，我们的方法大幅降低了目标预测误差，证明基于语言条件的预测能提升预测精度。基于无塔台机场的真实世界数据集进行的实验验证了该方法，并凸显了其在实现具备社会感知能力、基于语言条件的机器人运动规划上的潜力。

> Autonomous aircraft must safely operate in untowered airspace, where coordination relies on voice-based communication among human pilots. Safe operation requires an aircraft to predict the intent, and corresponding goal location, of other aircraft. This paper introduces a multimodal framework for aircraft goal prediction that integrates natural language understanding with spatial reasoning to improve autonomous decision-making in such environments. We leverage automatic speech recognition and large language models to transcribe and interpret pilot radio calls, identify aircraft, and extract discrete intent labels. These intent labels are fused with observed trajectories to condition a temporal convolutional network and Gaussian mixture model for probabilistic goal prediction. Our method significantly reduces goal prediction error compared to baselines that rely solely on motion history, demonstrating that language-conditioned prediction increases prediction accuracy. Experiments on a real-world dataset from an untowered airport validate the approach and highlight its potential to enable socially aware, language-conditioned robotic motion planning.

[Arxiv](https://arxiv.org/abs/2509.14063)