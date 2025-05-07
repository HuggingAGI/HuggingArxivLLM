# PhysLLM：利用大型语言模型实现跨模态远程生理感知

发布时间：2025年05月06日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于远程光体积描记法（rPPG）技术，解决其在处理生理信号时的挑战。通过提出协同优化框架PhysLLM，结合LLMs和特定领域的rPPG组件，展示了LLMs在实际应用中的潜力和效果。因此，这篇论文属于LLM应用类别。` `生物医学工程` `计算机视觉`

> PhysLLM: Harnessing Large Language Models for Cross-Modal Remote Physiological Sensing

# 摘要

> 远程光体积描记法 (rPPG) 虽然实现了非接触式生理测量，但易受光照变化、运动伪影和时间建模限制的影响。大型语言模型 (LLMs) 虽然在捕捉长距离依赖方面表现出色，但因其以文本为中心的设计，难以有效处理 rPPG 信号的连续性和噪声敏感性。为解决这一难题，我们提出了 PhysLLM，一个协同优化框架，将 LLMs 与特定领域的 rPPG 组件相结合。具体而言，我们提出了文本原型引导 (TPG) 策略，通过将血流动力学特征投影到 LLM 可解释的语义空间，实现了跨模态对齐，有效弥合了生理信号与语言令牌之间的表示差距。此外，我们还提出了一种新型双域静止 (DDS) 算法，通过自适应时频域特征重加权来解决信号不稳定问题。最后，rPPG 任务特定提示通过生理统计、环境上下文回答和任务描述系统地注入生理先验，利用跨模态学习整合视觉和文本信息，使模型能够动态适应光照变化和受试者运动等具有挑战性的场景。在四个基准数据集上的评估表明，PhysLLM 实现了最先进的准确性和鲁棒性，展示了其在光照变化和运动场景下的优越泛化能力。

> Remote photoplethysmography (rPPG) enables non-contact physiological measurement but remains highly susceptible to illumination changes, motion artifacts, and limited temporal modeling. Large Language Models (LLMs) excel at capturing long-range dependencies, offering a potential solution but struggle with the continuous, noise-sensitive nature of rPPG signals due to their text-centric design. To bridge this gap, we introduce PhysLLM, a collaborative optimization framework that synergizes LLMs with domain-specific rPPG components. Specifically, the Text Prototype Guidance (TPG) strategy is proposed to establish cross-modal alignment by projecting hemodynamic features into LLM-interpretable semantic space, effectively bridging the representational gap between physiological signals and linguistic tokens. Besides, a novel Dual-Domain Stationary (DDS) Algorithm is proposed for resolving signal instability through adaptive time-frequency domain feature re-weighting. Finally, rPPG task-specific cues systematically inject physiological priors through physiological statistics, environmental contextual answering, and task description, leveraging cross-modal learning to integrate both visual and textual information, enabling dynamic adaptation to challenging scenarios like variable illumination and subject movements. Evaluation on four benchmark datasets, PhysLLM achieves state-of-the-art accuracy and robustness, demonstrating superior generalization across lighting variations and motion scenarios.

[Arxiv](https://arxiv.org/abs/2505.03621)