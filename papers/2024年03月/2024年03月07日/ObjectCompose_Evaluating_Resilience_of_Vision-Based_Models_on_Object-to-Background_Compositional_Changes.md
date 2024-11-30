# ObjectCompose 项目旨在评测视觉模型在面临对象与背景组合变化时的抗干扰能力。

发布时间：2024年03月07日

`Agent`

> ObjectCompose: Evaluating Resilience of Vision-Based Models on Object-to-Background Compositional Changes

# 摘要

> 随着视觉模型的大规模多模态训练及强大的通用性，探究其实战鲁棒性对于实际应用至关重要。本文旨在评估现有视觉模型在面对多样复杂的对象与背景关系变化时的稳健性。过去的研究通常采用合成数据集引发对象属性变化，或通过对真实图像进行变换模拟分布偏移，但最新的工作尝试利用大型语言模型和扩散模型创造背景变化，却往往难以精准操控变化内容，甚至可能破坏对象本质含义。相比之下，我们提出的新方法能在确保对象原有意义和外观不变的情况下，创造出丰富多样的对象与背景关系变化。为此，我们巧妙运用文本转图像、图像转文本以及图像转分割模型的强大生成力，自动生成一系列对象与背景变化案例。通过调整文本提示或优化文本转图像模型的潜在变量及文本嵌入，我们可以自然或对抗性地改变背景。这一创新手段让我们得以深入探究背景因素在衡量和理解深度神经网络鲁棒性与泛化性上的作用。我们改造了多个主流视觉数据集（如 ImageNet 和 COCO），添加了丰富逼真的背景元素，或是对背景施加色彩、纹理及对抗性变化。随后，我们广泛开展实验，系统分析视觉模型在不同任务中应对对象与背景关系变化的鲁棒性能。

> Given the large-scale multi-modal training of recent vision-based models and their generalization capabilities, understanding the extent of their robustness is critical for their real-world deployment. In this work, we evaluate the resilience of current vision-based models against diverse object-to-background context variations. The majority of robustness evaluation methods have introduced synthetic datasets to induce changes to object characteristics (viewpoints, scale, color) or utilized image transformation techniques (adversarial changes, common corruptions) on real images to simulate shifts in distributions. Recent works have explored leveraging large language models and diffusion models to generate changes in the background. However, these methods either lack in offering control over the changes to be made or distort the object semantics, making them unsuitable for the task. Our method, on the other hand, can induce diverse object-to-background changes while preserving the original semantics and appearance of the object. To achieve this goal, we harness the generative capabilities of text-to-image, image-to-text, and image-to-segment models to automatically generate a broad spectrum of object-to-background changes. We induce both natural and adversarial background changes by either modifying the textual prompts or optimizing the latents and textual embedding of text-to-image models. This allows us to quantify the role of background context in understanding the robustness and generalization of deep neural networks. We produce various versions of standard vision datasets (ImageNet, COCO), incorporating either diverse and realistic backgrounds into the images or introducing color, texture, and adversarial changes in the background. We conduct extensive experiment to analyze the robustness of vision-based models against object-to-background context variations across diverse tasks.

[Arxiv](https://arxiv.org/abs/2403.04701)