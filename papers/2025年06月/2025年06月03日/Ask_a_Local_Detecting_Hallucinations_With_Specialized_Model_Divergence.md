# Ask a Local：通过专用模型差异检测幻觉

发布时间：2025年06月03日

`LLM应用

理由：这篇论文专注于检测大型语言模型中的幻觉现象，并提出了一种名为“Ask a Local”的方法。该方法利用语言专业化模型的困惑度分布差异来识别幻觉片段，适用于多语言环境且无需特定调整。研究内容集中在如何应用LLM来解决幻觉检测问题，属于LLM的具体应用场景，因此归类为LLM应用。` `人工智能` `语言技术`

> Ask a Local: Detecting Hallucinations With Specialized Model Divergence

# 摘要

> 大型语言模型中的幻觉现象——即模型生成看似合理但事实错误的信息——为人工智能带来了严峻挑战。我们推出了一种名为“Ask a Local”的全新幻觉检测方法，该方法基于一个直觉：专业模型在遇到领域特定的不准确信息时会表现出更大的惊讶程度。我们的方法通过计算语言专业化模型困惑度分布之间的差异来识别潜在的幻觉片段。

这种方法特别适合多语言环境，因为它无需适应、依赖外部数据源或进行训练，即可自然扩展到多种语言。此外，我们选择了计算效率高的模型，从而提供了一种可扩展的解决方案，适用于各种语言和领域。

在涵盖14种语言的人工标注问答数据集上的实验结果表明，我们的方法在不同语言间表现出一致的性能，交并比（IoU）分数约为0.3，且斯皮尔曼相关系数相当。我们的模型在意大利语和加泰罗尼亚语上表现尤为突出，分别达到0.42和0.38的IoU分数，同时在跨语言应用中保持有效性，而无需进行特定语言的调整。我们开源了代码和架构，以促进多语言幻觉检测领域的进一步研究。

> Hallucinations in large language models (LLMs) - instances where models generate plausible but factually incorrect information - present a significant challenge for AI.
  We introduce "Ask a Local", a novel hallucination detection method exploiting the intuition that specialized models exhibit greater surprise when encountering domain-specific inaccuracies. Our approach computes divergence between perplexity distributions of language-specialized models to identify potentially hallucinated spans. Our method is particularly well-suited for a multilingual context, as it naturally scales to multiple languages without the need for adaptation, relying on external data sources, or performing training. Moreover, we select computationally efficient models, providing a scalable solution that can be applied to a wide range of languages and domains.
  Our results on a human-annotated question-answer dataset spanning 14 languages demonstrate consistent performance across languages, with Intersection-over-Union (IoU) scores around 0.3 and comparable Spearman correlation values. Our model shows particularly strong performance on Italian and Catalan, with IoU scores of 0.42 and 0.38, respectively, while maintaining cross-lingual effectiveness without language-specific adaptations. We release our code and architecture to facilitate further research in multilingual hallucination detection.

[Arxiv](https://arxiv.org/abs/2506.03357)