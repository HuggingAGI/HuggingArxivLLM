# Llasa: 扩展Llama语音合成的训练与推理计算能力

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进语音合成系统（TTS），并提出了一个名为Llasa的简洁框架。论文的核心在于如何通过扩展训练和推理计算来提升语音合成的自然度和准确性，这与LLM在实际应用中的使用密切相关。因此，这篇论文应被归类为LLM应用。` `语音合成`

> Llasa: Scaling Train-Time and Inference-Time Compute for Llama-based Speech Synthesis

# 摘要

> # 摘要
近期，基于文本的大型语言模型（LLMs），尤其是GPT系列和o1模型，展示了训练和推理计算扩展的有效性。然而，当前利用LLMs的顶尖TTS系统多为多阶段架构，需依赖独立模型（如LLM后的扩散模型），这使得在训练或测试阶段决定是否扩展特定模型变得复杂。本研究贡献如下：首先，我们探索了语音合成中训练和推理计算的扩展。其次，我们提出了一个简洁的语音合成框架Llasa，采用单层向量量化（VQ）编解码器和单一Transformer架构，与Llama等标准LLMs完全兼容。实验表明，扩展Llasa的训练计算持续提升了合成语音的自然度，并生成更复杂、准确的韵律模式。此外，从推理计算扩展的角度，我们在搜索过程中引入语音理解模型作为验证器，发现扩展推理计算使采样模式更倾向于特定验证器的偏好，从而增强了情感表达、音色一致性和内容准确性。同时，我们公开了TTS模型（1B、3B、8B）和编解码器模型的检查点及训练代码。

> Recent advances in text-based large language models (LLMs), particularly in the GPT series and the o1 model, have demonstrated the effectiveness of scaling both training-time and inference-time compute. However, current state-of-the-art TTS systems leveraging LLMs are often multi-stage, requiring separate models (e.g., diffusion models after LLM), complicating the decision of whether to scale a particular model during training or testing. This work makes the following contributions: First, we explore the scaling of train-time and inference-time compute for speech synthesis. Second, we propose a simple framework Llasa for speech synthesis that employs a single-layer vector quantizer (VQ) codec and a single Transformer architecture to fully align with standard LLMs such as Llama. Our experiments reveal that scaling train-time compute for Llasa consistently improves the naturalness of synthesized speech and enables the generation of more complex and accurate prosody patterns. Furthermore, from the perspective of scaling inference-time compute, we employ speech understanding models as verifiers during the search, finding that scaling inference-time compute shifts the sampling modes toward the preferences of specific verifiers, thereby improving emotional expressiveness, timbre consistency, and content accuracy. In addition, we released the checkpoint and training code for our TTS model (1B, 3B, 8B) and codec model publicly available.

[Arxiv](https://arxiv.org/abs/2502.04128)