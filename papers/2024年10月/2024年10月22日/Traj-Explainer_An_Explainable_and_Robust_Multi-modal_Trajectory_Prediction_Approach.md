# Traj-Explainer: 一种兼具可解释性与鲁棒性的多模态轨迹预测方法

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了自动驾驶车辆在复杂交通环境中的导航能力，特别是通过提出一种名为 Traj-Explainer 的可解释性轨迹预测模型来改进轨迹预测的可解释性。这涉及到智能体（自动驾驶车辆）在环境中的感知、推理和决策过程，因此属于Agent类别。` `自动驾驶`

> Traj-Explainer: An Explainable and Robust Multi-modal Trajectory Prediction Approach

# 摘要

> # 摘要
智能技术的进步显著提升了自动驾驶车辆在复杂交通环境中的导航能力，使其能够准确感知环境并预测轨迹。然而，现有研究往往忽视了场景智能体的联合推理，且轨迹预测模型缺乏可解释性，限制了其实际应用。为此，本文提出了一种名为 Traj-Explainer 的可解释性轨迹预测模型，旨在揭示预测的影响因素并理解其内在机制。Traj-Explainer 采用改进的条件扩散模型捕捉多模态轨迹模式，并结合改进的 Shapley 值模型合理评估全局和场景特征的重要性。我们在 Waymo、NGSIM、HighD 和 MoCAD 等多个轨迹预测数据集上进行了实验，结果表明识别出的输入因素与人类驾驶经验一致，验证了模型的有效性。代码已开源：url{https://anonymous.4open.science/r/Interpretable-Prediction}。

> Navigating complex traffic environments has been significantly enhanced by advancements in intelligent technologies, enabling accurate environment perception and trajectory prediction for automated vehicles. However, existing research often neglects the consideration of the joint reasoning of scenario agents and lacks interpretability in trajectory prediction models, thereby limiting their practical application in real-world scenarios. To this purpose, an explainability-oriented trajectory prediction model is designed in this work, named Explainable Conditional Diffusion based Multimodal Trajectory Prediction Traj-Explainer, to retrieve the influencing factors of prediction and help understand the intrinsic mechanism of prediction. In Traj-Explainer, a modified conditional diffusion is well designed to capture the scenario multimodal trajectory pattern, and meanwhile, a modified Shapley Value model is assembled to rationally learn the importance of the global and scenario features. Numerical experiments are carried out by several trajectory prediction datasets, including Waymo, NGSIM, HighD, and MoCAD datasets. Furthermore, we evaluate the identified input factors which indicates that they are in agreement with the human driving experience, indicating the capability of the proposed model in appropriately learning the prediction. Code available in our open-source repository: url{https://anonymous.4open.science/r/Interpretable-Prediction}.

[Arxiv](https://arxiv.org/abs/2410.16795)