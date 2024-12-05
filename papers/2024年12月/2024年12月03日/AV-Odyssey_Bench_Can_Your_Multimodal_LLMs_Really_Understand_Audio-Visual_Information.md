# AV-Odyssey 基准：您的多模态大语言模型真能理解视听信息吗？

发布时间：2024年12月03日

`LLM应用` `模型评估`

> AV-Odyssey Bench: Can Your Multimodal LLMs Really Understand Audio-Visual Information?

# 摘要

> 最近，像 GPT-4o、Gemini 1.5 Pro 以及 Reka Core 这样的多模态大型语言模型（MLLMs），已将能力拓展至涵盖视觉与音频模态。尽管这些模型在众多视听应用中表现出众，然而我们提出的 DeafTest 却显示，MLLMs 常常在人类觉得轻而易举的简单任务上遭遇困境：比如确定两个声音哪个更响亮，以及哪个音调更高。受此启发，我们推出了 AV-Odyssey Bench，这是一个综合性的视听基准，旨在评估这些 MLLMs 是否真能理解视听信息。该基准包含 4555 个精心打造的问题，每个问题都融合了文本、视觉和音频元素。要成功推断出答案，模型必须有效利用来自视觉和音频输入的线索。为确保对 MLLM 响应进行精准客观的评估，我们把问题设置为多项选择题，从而无需人工评估或 LLM 辅助评估。我们对一系列闭源和开源模型进行了基准测试，并总结了观察所得。通过揭示当前模型的局限性，我们期望为未来的数据集收集和模型开发提供有益的启示。

> Recently, multimodal large language models (MLLMs), such as GPT-4o, Gemini 1.5 Pro, and Reka Core, have expanded their capabilities to include vision and audio modalities. While these models demonstrate impressive performance across a wide range of audio-visual applications, our proposed DeafTest reveals that MLLMs often struggle with simple tasks humans find trivial: 1) determining which of two sounds is louder, and 2) determining which of two sounds has a higher pitch. Motivated by these observations, we introduce AV-Odyssey Bench, a comprehensive audio-visual benchmark designed to assess whether those MLLMs can truly understand the audio-visual information. This benchmark encompasses 4,555 carefully crafted problems, each incorporating text, visual, and audio components. To successfully infer answers, models must effectively leverage clues from both visual and audio inputs. To ensure precise and objective evaluation of MLLM responses, we have structured the questions as multiple-choice, eliminating the need for human evaluation or LLM-assisted assessment. We benchmark a series of closed-source and open-source models and summarize the observations. By revealing the limitations of current models, we aim to provide useful insight for future dataset collection and model development.

[Arxiv](https://arxiv.org/abs/2412.02611)