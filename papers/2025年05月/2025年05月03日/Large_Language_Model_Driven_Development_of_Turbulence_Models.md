# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月03日

`LLM应用` `流体力学` `湍流建模`

> Large Language Model Driven Development of Turbulence Models

# 摘要

> 人工智能（AI）在围棋、图像识别和蛋白质折叠等领域已达到人类水平的表现，这引发了关于人工智能奇点的展望——即机器不仅能够匹敌甚至超越人类推理能力。本文展示了在湍流建模背景下朝着这一愿景迈出的一步。通过将大型语言模型（LLM）DeepSeek-R1视为平等的合作伙伴，我们构建了一个闭环、迭代的工作流程，在该流程中，LLM提出、完善并推理了在不利压力梯度（APG）、系统旋转和表面粗糙度条件下的壁湍流模型。通过多轮涉及长链推理和事前与事后的评估交互，LLM生成了不仅重新发现已建立策略，还合成出优于基线壁模型的新模型。具体而言，它建议在模型中加入物质导数以捕捉APG流动中的历史效应，修改壁定律以考虑系统旋转，并开发基于表面统计的粗糙壁模型。与传统的数据驱动湍流建模方法——通常以人类设计的黑箱架构为特征——不同，本文开发的模型具有物理可解释性，并基于清晰的推理过程。

> Artificial intelligence (AI) has achieved human-level performance in specialized tasks such as Go, image recognition, and protein folding, raising the prospect of an AI singularity-where machines not only match but surpass human reasoning. Here, we demonstrate a step toward this vision in the context of turbulence modeling. By treating a large language model (LLM), DeepSeek-R1, as an equal partner, we establish a closed-loop, iterative workflow in which the LLM proposes, refines, and reasons about near-wall turbulence models under adverse pressure gradients (APGs), system rotation, and surface roughness. Through multiple rounds of interaction involving long-chain reasoning and a priori and a posteriori evaluations, the LLM generates models that not only rediscover established strategies but also synthesize new ones that outperform baseline wall models. Specifically, it recommends incorporating a material derivative to capture history effects in APG flows, modifying the law of the wall to account for system rotation, and developing rough-wall models informed by surface statistics. In contrast to conventional data-driven turbulence modeling-often characterized by human-designed, black-box architectures-the models developed here are physically interpretable and grounded in clear reasoning.

[Arxiv](https://arxiv.org/abs/2505.01681)