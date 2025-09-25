# 面向自动驾驶的视觉-语言模型通用伪装攻击

发布时间：2025年09月24日

`LLM应用` `交通运输`

> Universal Camouflage Attack on Vision-Language Models for Autonomous Driving

# 摘要

> 面向自动驾驶的视觉语言建模（VLM-AD）凭借多模态推理能力的显著提升，正成为一个极具潜力的研究方向。尽管VLM-AD拥有先进的推理能力，却仍难逃对抗性攻击的严重安全威胁——此类攻击通过精心设计的扰动误导模型决策。然而现有攻击方法面临明显挑战：1）物理对抗性攻击主要针对视觉模块，由于通常攻击低级感知组件，难以直接迁移至VLM-AD系统；2）针对VLM-AD的对抗性攻击则多集中于数字层面。为应对这些难题，我们提出了首个面向VLM-AD的通用伪装攻击（UCA）框架。与以往以优化logit层为核心的方法不同，UCA在特征空间中生成物理可实现的伪装纹理，这些纹理在不同用户命令和模型架构上泛化能力突出。鉴于VLM-AD中编码器和投影层存在的脆弱性，UCA引入了特征差异损失（FDL），以最大化干净图像与对抗性图像之间的表征差异。此外，UCA还采用了多尺度学习策略并调整采样比例，以提升其对现实场景中尺度变化和视角多样性的适应能力，进而提高训练稳定性。大量实验验证，UCA可在多种VLM-AD模型和驾驶场景下诱导错误驾驶指令，性能远超当前最先进的攻击方法（在3-P指标上提升30%）。此外，UCA在不同视角和动态条件下均表现出优异的攻击鲁棒性，彰显出巨大的实际部署潜力。

> Visual language modeling for automated driving is emerging as a promising research direction with substantial improvements in multimodal reasoning capabilities. Despite its advanced reasoning abilities, VLM-AD remains vulnerable to serious security threats from adversarial attacks, which involve misleading model decisions through carefully crafted perturbations. Existing attacks have obvious challenges: 1) Physical adversarial attacks primarily target vision modules. They are difficult to directly transfer to VLM-AD systems because they typically attack low-level perceptual components. 2) Adversarial attacks against VLM-AD have largely concentrated on the digital level. To address these challenges, we propose the first Universal Camouflage Attack (UCA) framework for VLM-AD. Unlike previous methods that focus on optimizing the logit layer, UCA operates in the feature space to generate physically realizable camouflage textures that exhibit strong generalization across different user commands and model architectures. Motivated by the observed vulnerability of encoder and projection layers in VLM-AD, UCA introduces a feature divergence loss (FDL) that maximizes the representational discrepancy between clean and adversarial images. In addition, UCA incorporates a multi-scale learning strategy and adjusts the sampling ratio to enhance its adaptability to changes in scale and viewpoint diversity in real-world scenarios, thereby improving training stability. Extensive experiments demonstrate that UCA can induce incorrect driving commands across various VLM-AD models and driving scenarios, significantly surpassing existing state-of-the-art attack methods (improving 30\% in 3-P metrics). Furthermore, UCA exhibits strong attack robustness under diverse viewpoints and dynamic conditions, indicating high potential for practical deployment.

[Arxiv](https://arxiv.org/abs/2509.20196)