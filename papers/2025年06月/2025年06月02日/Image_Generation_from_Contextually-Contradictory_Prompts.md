# 基于语境矛盾提示的图像生成

发布时间：2025年06月02日

`LLM应用` `图像生成` `文本到图像`

> Image Generation from Contextually-Contradictory Prompts

# 摘要

> 文本到图像的扩散模型擅长从自然语言提示生成高质量、多样的图像。然而，当提示中的概念组合与模型学习的先验知识相矛盾时，它们往往难以生成语义准确的结果。我们将这种失效模式定义为上下文矛盾，其中一个概念由于训练过程中学到的纠缠关联而隐式否定另一个概念。为了解决这一问题，我们提出了一种基于阶段感知的提示分解框架，该框架通过一系列代理提示引导去噪过程。每个代理提示都经过设计，以匹配在特定去噪阶段预期出现的语义内容，同时确保上下文连贯性。为了构建这些代理提示，我们利用大型语言模型（LLM）来分析目标提示，识别矛盾，并生成保留原始意图同时解决上下文冲突的替代表达。通过将提示信息与去噪进程对齐，我们的方法实现了对上下文矛盾存在情况下的细粒度语义控制和准确的图像生成。在各种具有挑战性的提示上的实验表明，与现有方法相比，我们的方法在与文本提示的对齐方面有了显著提升。

> Text-to-image diffusion models excel at generating high-quality, diverse images from natural language prompts. However, they often fail to produce semantically accurate results when the prompt contains concept combinations that contradict their learned priors. We define this failure mode as contextual contradiction, where one concept implicitly negates another due to entangled associations learned during training. To address this, we propose a stage-aware prompt decomposition framework that guides the denoising process using a sequence of proxy prompts. Each proxy prompt is constructed to match the semantic content expected to emerge at a specific stage of denoising, while ensuring contextual coherence. To construct these proxy prompts, we leverage a large language model (LLM) to analyze the target prompt, identify contradictions, and generate alternative expressions that preserve the original intent while resolving contextual conflicts. By aligning prompt information with the denoising progression, our method enables fine-grained semantic control and accurate image generation in the presence of contextual contradictions. Experiments across a variety of challenging prompts show substantial improvements in alignment to the textual prompt.

[Arxiv](https://arxiv.org/abs/2506.01929)