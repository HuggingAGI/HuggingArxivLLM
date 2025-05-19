# 探索音频大语言模型在检测音频深度伪造中的潜力

发布时间：2025年05月16日

`LLM应用

摘要分析：这篇论文探讨了如何将音频大型语言模型（ALLMs）应用于音频深度伪造检测（ADD）任务。通过提出基于ALLM的框架，并进行监督微调，提升了检测虚假音频的能力，尤其是在数据稀缺的场景下表现优异。这属于LLM的应用层面研究。` `音频处理` `语言模型`

> : Unlocking the Capabilities of Audio Large Language Models for Audio Deepfake Detection

# 摘要

> 随着高保真音频生成模型的兴起及其滥用风险的增加，音频深度伪造检测（ADD）变得日益重要。鉴于音频大型语言模型（ALLMs）在各类音频处理任务中取得了显著进展，一个启发性的问题随之而来：能否利用ALLMs来解决ADD问题？本文首先对ALLMs在ADD任务上进行了全面的零样本评估，发现其在检测虚假音频方面表现不佳。为提升其性能，我们提出了【数学公式】，一个基于ALLM的ADD框架。具体而言，我们将ADD任务重新定义为一个音频问答问题，并以问题"这段音频是伪造的还是真实的？"来提示模型。随后，我们进行监督微调，使ALLM能够评估查询音频的真实性。通过大量实验，我们证明了基于ALLM的方法在虚假音频检测中能够实现优越性能，尤其是在数据稀缺的场景下。作为开创性研究，我们期待这项工作能够启发研究界利用ALLMs开发出更有效的ADD系统。

> Audio deepfake detection (ADD) has grown increasingly important due to the rise of high-fidelity audio generative models and their potential for misuse. Given that audio large language models (ALLMs) have made significant progress in various audio processing tasks, a heuristic question arises: Can ALLMs be leveraged to solve ADD?. In this paper, we first conduct a comprehensive zero-shot evaluation of ALLMs on ADD, revealing their ineffectiveness in detecting fake audio. To enhance their performance, we propose $\mathcal{A}LLM4ADD$, an ALLM-driven framework for ADD. Specifically, we reformulate ADD task as an audio question answering problem, prompting the model with the question: "Is this audio fake or real?". We then perform supervised fine-tuning to enable the ALLM to assess the authenticity of query audio. Extensive experiments are conducted to demonstrate that our ALLM-based method can achieve superior performance in fake audio detection, particularly in data-scarce scenarios. As a pioneering study, we anticipate that this work will inspire the research community to leverage ALLMs to develop more effective ADD systems.

[Arxiv](https://arxiv.org/abs/2505.11079)