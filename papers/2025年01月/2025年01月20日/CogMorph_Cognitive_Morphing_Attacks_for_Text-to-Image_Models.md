# CogMorph: 文本到图像模型的认知变形攻击

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了文本到图像（T2I）生成模型的伦理风险，并提出了一种名为认知变形攻击（CogMorph）的新方法。虽然论文涉及图像生成，但其核心是通过操纵T2I模型来生成有害图像，这与大型语言模型（LLM）的应用场景密切相关。因此，将其归类为“LLM应用”是合适的。` `创意设计` `内容生成`

> CogMorph: Cognitive Morphing Attacks for Text-to-Image Models

# 摘要

> # 摘要
文本到图像（T2I）生成模型的进步，使得从文本生成高质量图像成为可能，为创意设计和内容生成开辟了新天地。然而，本文揭示了一项此前未被察觉的重大伦理风险，并提出了一种名为认知变形攻击（CogMorph）的新方法。该方法通过操纵T2I模型，生成保留原始主题但嵌入有害元素的图像，利用人类认知中对场景和上下文的依赖，放大情感伤害。为应对这一挑战，我们构建了一个涵盖10大类、48小类的图像毒性分类法，并基于人类认知感知维度，生成了1,176个高质量的有毒提示。CogMorph首先通过认知毒性增强，构建了一个包含丰富外部毒性表示的知识库，用于优化对抗性提示。此外，我们提出了上下文层次变形，通过层次化提取原始提示的关键部分，并迭代融合有毒特征，注入有害上下文。在多个开源T2I模型和商业API（如DALLE-3）上的实验表明，CogMorph显著优于其他基线，平均提升20.62%。

> The development of text-to-image (T2I) generative models, that enable the creation of high-quality synthetic images from textual prompts, has opened new frontiers in creative design and content generation. However, this paper reveals a significant and previously unrecognized ethical risk inherent in this technology and introduces a novel method, termed the Cognitive Morphing Attack (CogMorph), which manipulates T2I models to generate images that retain the original core subjects but embeds toxic or harmful contextual elements. This nuanced manipulation exploits the cognitive principle that human perception of concepts is shaped by the entire visual scene and its context, producing images that amplify emotional harm far beyond attacks that merely preserve the original semantics. To address this, we first construct an imagery toxicity taxonomy spanning 10 major and 48 sub-categories, aligned with human cognitive-perceptual dimensions, and further build a toxicity risk matrix resulting in 1,176 high-quality T2I toxic prompts. Based on this, our CogMorph first introduces Cognitive Toxicity Augmentation, which develops a cognitive toxicity knowledge base with rich external toxic representations for humans (e.g., fine-grained visual features) that can be utilized to further guide the optimization of adversarial prompts. In addition, we present Contextual Hierarchical Morphing, which hierarchically extracts critical parts of the original prompt (e.g., scenes, subjects, and body parts), and then iteratively retrieves and fuses toxic features to inject harmful contexts. Extensive experiments on multiple open-sourced T2I models and black-box commercial APIs (e.g., DALLE-3) demonstrate the efficacy of CogMorph which significantly outperforms other baselines by large margins (+20.62\% on average).

[Arxiv](https://arxiv.org/abs/2501.11815)