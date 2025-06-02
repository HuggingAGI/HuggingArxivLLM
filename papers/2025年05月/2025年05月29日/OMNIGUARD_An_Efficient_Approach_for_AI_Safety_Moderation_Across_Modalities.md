# # OMNIGUARD: 跨模态 AI 安全内容审核的高效方法

发布时间：2025年05月29日

`LLM应用` `跨模态`

> OMNIGUARD: An Efficient Approach for AI Safety Moderation Across Modalities

# 摘要

> 大型语言模型（LLMs）的崛起引发了对其可能被恶意滥用的担忧。为缓解这些担忧，我们提出了一种核心方法——检测对模型的有害查询。现有的检测方法并不完美，尤其容易受到利用模型能力泛化差异的攻击（例如，使用低资源语言的提示或非文本模态如图像和音频提供的提示）。为应对这一挑战，我们提出了OMNIGUARD，一种跨语言和模态检测有害提示的方法。我们的方法通过（i）识别LLM/MLLM中跨语言或跨模态对齐的内部表征，然后（ii）利用这些表征构建一种语言无关或模态无关的分类器，用于检测有害提示。在多语言设置下，OMNIGUARD将有害提示分类准确率提高了11.57%，在图像提示中提高了20.44%，并为音频提示设定了新的SOTA。通过复用生成过程中计算的嵌入，OMNIGUARD也非常高效（比最快的基线快约120倍）。项目地址：[GitHub链接]。


> The emerging capabilities of large language models (LLMs) have sparked concerns about their immediate potential for harmful misuse. The core approach to mitigate these concerns is the detection of harmful queries to the model. Current detection approaches are fallible, and are particularly susceptible to attacks that exploit mismatched generalization of model capabilities (e.g., prompts in low-resource languages or prompts provided in non-text modalities such as image and audio). To tackle this challenge, we propose OMNIGUARD, an approach for detecting harmful prompts across languages and modalities. Our approach (i) identifies internal representations of an LLM/MLLM that are aligned across languages or modalities and then (ii) uses them to build a language-agnostic or modality-agnostic classifier for detecting harmful prompts. OMNIGUARD improves harmful prompt classification accuracy by 11.57\% over the strongest baseline in a multilingual setting, by 20.44\% for image-based prompts, and sets a new SOTA for audio-based prompts. By repurposing embeddings computed during generation, OMNIGUARD is also very efficient ($\approx 120 \times$ faster than the next fastest baseline). Code and data are available at: https://github.com/vsahil/OmniGuard.

[Arxiv](https://arxiv.org/abs/2505.23856)