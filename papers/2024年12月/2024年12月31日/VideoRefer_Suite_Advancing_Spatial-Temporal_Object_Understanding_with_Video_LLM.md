# VideoRefer Suite：利用视频LLM提升时空对象理解能力

发布时间：2024年12月31日

`LLM应用

理由：这篇论文主要讨论了视频大语言模型（Video LLMs）在细粒度时空视频理解上的应用，并提出了VideoRefer Suite来提升模型的能力。论文的核心内容围绕数据集、模型和基准的构建，这些都是LLM在实际应用中的具体实现和优化。因此，这篇论文应归类为LLM应用。` `视频理解` `人工智能`

> VideoRefer Suite: Advancing Spatial-Temporal Object Understanding with Video LLM

# 摘要

> # 摘要
视频大语言模型（Video LLMs）在通用视频理解方面展现了卓越能力，但主要局限于整体理解，难以捕捉细粒度的时空细节。此外，高质量对象级视频指令数据的匮乏和全面基准的缺失，进一步制约了其发展。为此，我们推出了VideoRefer Suite，旨在提升Video LLM在细粒度时空视频理解上的能力，使其能够对视频中的任意对象进行感知和推理。我们围绕数据集、模型和基准三大核心，全面构建了VideoRefer Suite。首先，通过多智能体数据引擎，我们精心打造了大规模、高质量的对象级视频指令数据集VideoRefer-700K。其次，我们推出了VideoRefer模型，配备多功能时空对象编码器，精准捕捉区域与序列特征。最后，我们精心设计了VideoRefer-Bench，全面评估Video LLM的时空理解能力。大量实验与分析表明，VideoRefer模型不仅在视频引用基准上表现优异，还显著提升了通用视频理解能力。

> Video Large Language Models (Video LLMs) have recently exhibited remarkable capabilities in general video understanding. However, they mainly focus on holistic comprehension and struggle with capturing fine-grained spatial and temporal details. Besides, the lack of high-quality object-level video instruction data and a comprehensive benchmark further hinders their advancements. To tackle these challenges, we introduce the VideoRefer Suite to empower Video LLM for finer-level spatial-temporal video understanding, i.e., enabling perception and reasoning on any objects throughout the video. Specially, we thoroughly develop VideoRefer Suite across three essential aspects: dataset, model, and benchmark. Firstly, we introduce a multi-agent data engine to meticulously curate a large-scale, high-quality object-level video instruction dataset, termed VideoRefer-700K. Next, we present the VideoRefer model, which equips a versatile spatial-temporal object encoder to capture precise regional and sequential representations. Finally, we meticulously create a VideoRefer-Bench to comprehensively assess the spatial-temporal understanding capability of a Video LLM, evaluating it across various aspects. Extensive experiments and analyses demonstrate that our VideoRefer model not only achieves promising performance on video referring benchmarks but also facilitates general video understanding capabilities.

[Arxiv](https://arxiv.org/abs/2501.00599)