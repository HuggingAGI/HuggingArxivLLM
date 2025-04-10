# JailDAM：面向视觉语言模型的越狱检测与自适应记忆机制

发布时间：2025年04月08日

`LLM应用`

> JailDAM: Jailbreak Detection with Adaptive Memory for Vision-Language Model

# 摘要

> 多模态大语言模型（MLLMs）在视觉语言任务中表现出色，但同时也带来了生成有害内容的重大风险，尤其是在越狱攻击方面。越狱攻击指的是有意规避模型安全机制，导致生成不适当或不安全内容的行为。检测此类攻击对于确保MLLMs的负责任部署至关重要。然而，现有的越狱攻击检测方法面临三大主要挑战：（1）现有方法大多依赖模型隐藏状态或梯度，导致其仅适用于白盒模型，即内部机制可被访问的模型；（2）基于不确定性的分析带来了高昂的计算开销，限制了实时检测的实现；（3）现有方法通常需要完整的有害数据标注集，而这类数据在实际场景中往往难以获取。为了解决这些问题，我们提出了一种名为JAILDAM的测试时自适应框架。我们的方法采用基于策略驱动的不安全知识表示的内存方法，无需显式接触有害数据。通过在测试时动态更新不安全知识，我们的框架不仅保持了高效性，还提升了对未知越狱策略的泛化能力。在多个VLM越狱基准测试上的实验结果表明，JAILDAM在有害内容检测方面达到了最先进的性能，同时显著提升了准确性和检测速度。

> Multimodal large language models (MLLMs) excel in vision-language tasks but also pose significant risks of generating harmful content, particularly through jailbreak attacks. Jailbreak attacks refer to intentional manipulations that bypass safety mechanisms in models, leading to the generation of inappropriate or unsafe content. Detecting such attacks is critical to ensuring the responsible deployment of MLLMs. Existing jailbreak detection methods face three primary challenges: (1) Many rely on model hidden states or gradients, limiting their applicability to white-box models, where the internal workings of the model are accessible; (2) They involve high computational overhead from uncertainty-based analysis, which limits real-time detection, and (3) They require fully labeled harmful datasets, which are often scarce in real-world settings. To address these issues, we introduce a test-time adaptive framework called JAILDAM. Our method leverages a memory-based approach guided by policy-driven unsafe knowledge representations, eliminating the need for explicit exposure to harmful data. By dynamically updating unsafe knowledge during test-time, our framework improves generalization to unseen jailbreak strategies while maintaining efficiency. Experiments on multiple VLM jailbreak benchmarks demonstrate that JAILDAM delivers state-of-the-art performance in harmful content detection, improving both accuracy and speed.

[Arxiv](https://arxiv.org/abs/2504.03770)