# 犯罪行为预测框架 MA-CBP: 基于多智能体异步协作

发布时间：2025年08月08日

`Agent` `公共安全` `视频分析`

> MA-CBP: A Criminal Behavior Prediction Framework Based on Multi-Agent Asynchronous Collaboration

# 摘要

> 城市化进程的加速使得公共场景中的犯罪行为对社会安全构成日益严峻的威胁。传统基于特征识别的异常检测方法难以从历史信息中提取出高级行为语义，而基于大型语言模型（LLMs）的生成方法又常常无法满足实时性要求。针对这些挑战，我们提出了MA-CBP——一个基于多智能体异步协作的犯罪行为预测框架。该框架能够将实时视频流转化为帧级语义描述，构建因果一致的历史摘要，并通过融合相邻图像帧，实现对长短期上下文的联合推理。最终得出的行为决策涵盖了事件主体、地点及原因等关键要素，从而实现对潜在犯罪行为的早期预警。此外，我们还构建了一个高质量的犯罪行为数据集，提供多尺度的语言监督，包括帧级、摘要级和事件级的语义标注。实验结果表明，我们的方法在多个数据集上表现优异，为城市公共安全场景中的风险预警提供了极具前景的解决方案。

> With the acceleration of urbanization, criminal behavior in public scenes poses an increasingly serious threat to social security. Traditional anomaly detection methods based on feature recognition struggle to capture high-level behavioral semantics from historical information, while generative approaches based on Large Language Models (LLMs) often fail to meet real-time requirements. To address these challenges, we propose MA-CBP, a criminal behavior prediction framework based on multi-agent asynchronous collaboration. This framework transforms real-time video streams into frame-level semantic descriptions, constructs causally consistent historical summaries, and fuses adjacent image frames to perform joint reasoning over long- and short-term contexts. The resulting behavioral decisions include key elements such as event subjects, locations, and causes, enabling early warning of potential criminal activity. In addition, we construct a high-quality criminal behavior dataset that provides multi-scale language supervision, including frame-level, summary-level, and event-level semantic annotations. Experimental results demonstrate that our method achieves superior performance on multiple datasets and offers a promising solution for risk warning in urban public safety scenarios.

[Arxiv](https://arxiv.org/abs/2508.06189)