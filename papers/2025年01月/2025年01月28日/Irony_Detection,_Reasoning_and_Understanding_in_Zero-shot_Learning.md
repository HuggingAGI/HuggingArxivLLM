# 零-shot 学习中的反讽检测、推理与理解

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要探讨了ChatGPT在讽刺检测任务中的表现，并提出了一个提示工程设计框架IDADP来提升其性能。研究重点在于如何利用大型语言模型（LLM）来解决具体的NLP任务（讽刺检测），并提出了改进模型应用效果的方法。因此，这篇论文属于LLM应用类别。` `社交媒体`

> Irony Detection, Reasoning and Understanding in Zero-shot Learning

# 摘要

> # 摘要
讽刺是社交媒体上一种强大的比喻语言（FL），可能误导推荐系统、虚假信息检查和情感分析等NLP任务。理解这种微妙语言的隐含意义对减轻其负面影响至关重要。然而，构建理解讽刺的模型面临独特挑战，因为讽刺依赖上下文、语气和微妙线索传达与字面相反的意义。像ChatGPT这样的大型语言模型逐渐能捕捉隐含信息。本研究探讨了ChatGPT在六个不同体裁讽刺检测数据集上的泛化、推理和理解能力。结果显示，ChatGPT表现出增强的语言理解和推理能力，但在提示工程设计上需格外谨慎。为此，我们提出了提示工程设计框架IDADP，相比其他最先进的ChatGPT零-shot方法，IDADP在讽刺检测准确性、理解和解释上表现更优。实验证实，该框架下的实践可能是解决LLMs泛化问题的有效方案。

> Irony is a powerful figurative language (FL) on social media that can potentially mislead various NLP tasks, such as recommendation systems, misinformation checks, and sentiment analysis. Understanding the implicit meaning of this kind of subtle language is essential to mitigate irony's negative impact on NLP tasks. However, building models to understand irony presents a unique set of challenges, because irony is a complex form of language that often relies on context, tone, and subtle cues to convey meaning that is opposite or different from the literal interpretation. Large language models, such as ChatGPT, are increasingly able to capture implicit and contextual information. In this study, we investigate the generalization, reasoning and understanding ability of ChatGPT on irony detection across six different genre irony detection datasets. Our findings suggest that ChatGPT appears to show an enhanced language understanding and reasoning ability. But it needs to be very careful in prompt engineering design. Thus, we propose a prompt engineering design framework IDADP to achieve higher irony detection accuracy, improved understanding of irony, and more effective explanations compared to other state-of-the-art ChatGPT zero-shot approaches. And ascertain via experiments that the practice generated under the framework is likely to be the promised solution to resolve the generalization issues of LLMs.

[Arxiv](https://arxiv.org/abs/2501.16884)