# PixFoundation: 像素级视觉基础模型，我们走对路了吗？

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在像素级理解和视觉问答任务中的应用，提出了新的基准测试和基线方法（PixFoundation），并探讨了无像素级监督训练的MLLMs的定位能力。这些内容属于LLM在实际任务中的应用和改进，因此归类为LLM应用。` `计算机视觉`

> PixFoundation: Are We Heading in the Right Direction with Pixel-level Vision Foundation Models?

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在像素级理解方面不断突破，尤其在指代表达分割和对话生成基准测试中表现优异。当前主流方法依赖于大规模标注数据的像素级监督训练。然而，这些MLLMs在面对最新视觉中心基准测试时，视觉问答能力却显得薄弱。更令人意外的是，某些方法甚至削弱了从未接受过此类监督训练的MLLMs的定位能力。为此，我们提出了两个全新挑战性基准测试，证明无像素级监督训练的MLLMs在像素级定位和视觉问答任务中能超越现有技术。我们开发了名为PixFoundation的简单基线方法，可轻松集成到任何MLLM中，用于提取定位信息。更重要的是，我们探讨了“无像素级监督训练的MLLMs何时具备定位能力？”这一问题，发现定位能力可能与物体部分或位置/外观信息同步出现。代码库已开源：https://github.com/MSiam/PixFoundation/。

> Multiple works have emerged to push the boundaries on multi-modal large language models (MLLMs) towards pixel-level understanding. Such approaches have shown strong performance on benchmarks for referring expression segmentation and grounded conversation generation. The current trend in pixel-level MLLMs is to train with pixel-level grounding supervision on large-scale labelled data. However, we show that such MLLMs when evaluated on recent challenging vision centric benchmarks, exhibit a weak ability in visual question answering. Surprisingly, some of these methods even downgrade the grounding ability of MLLMs that were never trained with such supervision. In this work, we propose two novel challenging benchmarks and show that MLLMs without pixel-level grounding supervision can outperform the state of the art in such tasks when evaluating both the pixel-level grounding and visual question answering. We propose simple baselines to extract the grounding information that can be plugged into any MLLM, which we call as PixFoundation. More importantly, we study the research question of ``When does grounding emerge in MLLMs that are not trained with pixel-level grounding supervision?'' We show that grounding can coincide with object parts or location/appearance information. Code repository is at https://github.com/MSiam/PixFoundation/.

[Arxiv](https://arxiv.org/abs/2502.04192)