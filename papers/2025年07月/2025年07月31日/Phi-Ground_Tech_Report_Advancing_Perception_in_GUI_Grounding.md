# Phi-Ground 技术报告：推动图形用户界面（GUI）锚定技术的感知能力提升

发布时间：2025年07月31日

`Agent

理由：这篇论文专注于提升计算机使用代理（CUAs）在GUI接地任务中的性能，探讨了模型训练和实际应用，属于Agent领域。` `人工智能` `计算机科学`

> Phi-Ground Tech Report: Advancing Perception in GUI Grounding

# 摘要

> 随着多模态推理模型的发展，类似《钢铁侠》中 Jarvis 的计算机使用代理 (CUAs) 正在成为现实。GUI 接地（GUI grounding）作为 CUAs 执行实际操作的核心组件，类似于机器人学中的机械控制，直接决定了系统的成功与否。它不仅决定了点击和输入等基础操作，还涵盖了点击坐标等关键参数。然而，目前的端到端接地模型在 ScreenSpot-pro 和 UI-Vision 等具有挑战性的基准测试中仍低于 65% 的准确率，表明它们距离实际部署仍有较大差距。在本研究中，我们对接地模型的训练进行了全面的实证研究，从数据收集到模型训练的每一个环节都进行了深入探讨。最终，我们成功开发了 	extbf{Phi-Ground} 模型系列，在所有五项针对 agent 设置下 10B 参数以下模型的接地基准测试中均达到了最先进的性能。在端到端模型设置下，我们的模型在 ScreenSpot-pro 上获得了 	extit{	extbf{43.2}} 的分数，在 UI-Vision 上获得了 	extit{	extbf{27.2}} 的分数，依然实现了最优结果。我们相信，本文中探讨的诸多细节，以及我们的成功与失败经验，不仅为接地模型的构建提供了清晰的指导，还将对其他感知任务产生积极的影响。项目主页：\href{https://zhangmiaosen2000.github.io/Phi-Ground/}{https://zhangmiaosen2000.github.io/Phi-Ground/}

> With the development of multimodal reasoning models, Computer Use Agents (CUAs), akin to Jarvis from \textit{"Iron Man"}, are becoming a reality. GUI grounding is a core component for CUAs to execute actual actions, similar to mechanical control in robotics, and it directly leads to the success or failure of the system. It determines actions such as clicking and typing, as well as related parameters like the coordinates for clicks. Current end-to-end grounding models still achieve less than 65\% accuracy on challenging benchmarks like ScreenSpot-pro and UI-Vision, indicating they are far from being ready for deployment. % , as a single misclick can result in unacceptable consequences. In this work, we conduct an empirical study on the training of grounding models, examining details from data collection to model training. Ultimately, we developed the \textbf{Phi-Ground} model family, which achieves state-of-the-art performance across all five grounding benchmarks for models under $10B$ parameters in agent settings. In the end-to-end model setting, our model still achieves SOTA results with scores of \textit{\textbf{43.2}} on ScreenSpot-pro and \textit{\textbf{27.2}} on UI-Vision. We believe that the various details discussed in this paper, along with our successes and failures, not only clarify the construction of grounding models but also benefit other perception tasks. Project homepage: \href{https://zhangmiaosen2000.github.io/Phi-Ground/}{https://zhangmiaosen2000.github.io/Phi-Ground/}

[Arxiv](https://arxiv.org/abs/2507.23779)