# SceneTAP：现实环境中针对视觉语言模型的场景连贯排版对抗规划器

发布时间：2024年11月28日

`LLM应用` `计算机视觉` `人工智能安全`

> SceneTAP: Scene-Coherent Typographic Adversarial Planner against Vision-Language Models in Real-World Environments

# 摘要

> 大型视觉语言模型（LVLMs）在解读视觉内容方面展现出非凡能力。然而，现有研究显示这些模型易受刻意设置的对抗性文本影响，且此类文本往往容易被识别为异常。本文中，我们率先提出生成场景一致的排版对抗性攻击的方法，能误导先进的 LVLMs，同时借助基于 LLM 的代理能力保持视觉自然性。我们的方法解决了三个关键问题：生成何种对抗性文本、置于场景何处以及如何无缝融合。我们提出一种无需训练、多模态且由 LLM 驱动的场景一致排版对抗性规划（SceneTAP），它采用三阶段流程：场景理解、对抗性规划和无缝集成。SceneTAP 利用思维链推理理解场景、制定有效的对抗性文本、策略性规划其位置，并给出在图像中自然融合的详细指令。接着是场景一致的 TextDiffuser，它通过局部扩散机制实施攻击。我们通过在实际环境中打印并放置生成的补丁，将方法拓展到现实场景，展示了其实用价值。大量实验表明，我们的场景一致对抗性文本成功误导了包括 ChatGPT-4o 在内的前沿 LVLMs，即便在拍摄物理设置的新图像之后。我们的评估显示，在保持视觉自然性和上下文适宜性的同时，攻击成功率大幅提升。此项工作凸显了当前视觉语言模型面对复杂、场景一致的对抗性攻击时的脆弱性，并为潜在防御机制提供了思路。

> Large vision-language models (LVLMs) have shown remarkable capabilities in interpreting visual content. While existing works demonstrate these models' vulnerability to deliberately placed adversarial texts, such texts are often easily identifiable as anomalous. In this paper, we present the first approach to generate scene-coherent typographic adversarial attacks that mislead advanced LVLMs while maintaining visual naturalness through the capability of the LLM-based agent. Our approach addresses three critical questions: what adversarial text to generate, where to place it within the scene, and how to integrate it seamlessly. We propose a training-free, multi-modal LLM-driven scene-coherent typographic adversarial planning (SceneTAP) that employs a three-stage process: scene understanding, adversarial planning, and seamless integration. The SceneTAP utilizes chain-of-thought reasoning to comprehend the scene, formulate effective adversarial text, strategically plan its placement, and provide detailed instructions for natural integration within the image. This is followed by a scene-coherent TextDiffuser that executes the attack using a local diffusion mechanism. We extend our method to real-world scenarios by printing and placing generated patches in physical environments, demonstrating its practical implications. Extensive experiments show that our scene-coherent adversarial text successfully misleads state-of-the-art LVLMs, including ChatGPT-4o, even after capturing new images of physical setups. Our evaluations demonstrate a significant increase in attack success rates while maintaining visual naturalness and contextual appropriateness. This work highlights vulnerabilities in current vision-language models to sophisticated, scene-coherent adversarial attacks and provides insights into potential defense mechanisms.

[Arxiv](https://arxiv.org/abs/2412.00114)