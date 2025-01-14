# 基于传感器的开放词汇活动识别初步研究：文本嵌入反转的应用

发布时间：2025年01月13日

`LLM应用

理由：这篇论文提出了开放词汇人类活动识别（OV-HAR），通过将活动转换为自然语言并利用预训练的嵌入反演模型进行解码，实现了开放词汇识别。虽然论文中提到了使用LLM提示工程将生成的文本转换为单一活动类别，但核心方法并不直接依赖于自回归LLMs，而是通过嵌入和反演模型来实现。因此，这篇论文主要属于LLM应用的范畴，因为它利用了LLM相关的技术（如嵌入和提示工程）来解决实际问题。` `人类活动识别` `传感器`

> Initial Findings on Sensor based Open Vocabulary Activity Recognition via Text Embedding Inversion

# 摘要

> 传统的人类活动识别（HAR）依赖于分类器预测离散活动类别，这限制了识别范围仅限于训练集中明确存在的活动。当遇到未见过的活动时，这些分类器必然失败。我们提出了开放词汇HAR（OV-HAR），通过将活动转换为自然语言并分解为基本动作序列，克服了这一限制。描述性文本被编码为固定大小的嵌入，模型通过回归该嵌入进行训练，并使用预训练的嵌入反演模型将其解码回自然语言。与依赖自回归LLMs的工作不同，OV-HAR在不增加计算开销的情况下实现了开放词汇识别。生成的文本可通过LLM提示工程转换为单一活动类别。我们在视觉（姿态）、IMU和压力传感器等多种模态上评估了该方法，展示了在未见过的活动和模态上的强大泛化能力，提供了一个与当代分类器截然不同的范式。

> Conventional human activity recognition (HAR) relies on classifiers trained to predict discrete activity classes, inherently limiting recognition to activities explicitly present in the training set. Such classifiers would invariably fail, putting zero likelihood, when encountering unseen activities. We propose Open Vocabulary HAR (OV-HAR), a framework that overcomes this limitation by first converting each activity into natural language and breaking it into a sequence of elementary motions. This descriptive text is then encoded into a fixed-size embedding. The model is trained to regress this embedding, which is subsequently decoded back into natural language using a pre-trained embedding inversion model. Unlike other works that rely on auto-regressive large language models (LLMs) at their core, OV-HAR achieves open vocabulary recognition without the computational overhead of such models. The generated text can be transformed into a single activity class using LLM prompt engineering. We have evaluated our approach on different modalities, including vision (pose), IMU, and pressure sensors, demonstrating robust generalization across unseen activities and modalities, offering a fundamentally different paradigm from contemporary classifiers.

[Arxiv](https://arxiv.org/abs/2501.07408)