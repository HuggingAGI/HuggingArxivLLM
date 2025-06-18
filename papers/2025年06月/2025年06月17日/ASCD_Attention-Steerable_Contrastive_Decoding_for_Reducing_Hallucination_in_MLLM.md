# ASCD：通过可引导注意力的对比解码，减少多语言大语言模型中的幻觉

发布时间：2025年06月17日

`LLM理论` `人工智能` `生成模型`

> ASCD: Attention-Steerable Contrastive Decoding for Reducing Hallucination in MLLM

# 摘要

> 多模态大型语言模型（MLLM）常因过度依赖不完整提示信息而产生幻觉，生成错误回应。近期，研究者提出了视觉对比解码（VCD）和指令对比解码（ICD）等方法，通过对比扰动或负前缀输入的预测与原始输出，来缓解幻觉问题。我们深入探究发现，VCD和ICD等方法从根本上改变了模型的内部注意力机制，其有效性不仅源于对模型输出的表面修改，更源于注意力分布的深层改变。基于这一发现，我们提出了一种可控制的对比解码框架，直接干预模型的注意力机制，从而以更系统化的方式缓解幻觉问题。实验结果表明，我们的方法在多种MLLM架构和解码方法下均显著降低了幻觉现象，并在POPE、CHAIR和MMHal-Bench等基准测试中提升了性能，同时也在标准的视觉问答（VQA）基准上取得了更好的效果。

> Multimodal Large Language Model (MLLM) often suffer from hallucinations. They over-rely on partial cues and generate incorrect responses. Recently, methods like Visual Contrastive Decoding (VCD) and Instruction Contrastive Decoding (ICD) have been proposed to mitigate hallucinations by contrasting predictions from perturbed or negatively prefixed inputs against original outputs. In this work, we uncover that methods like VCD and ICD fundamentally influence internal attention dynamics of the model. This observation suggests that their effectiveness may not stem merely from surface-level modifications to logits but from deeper shifts in attention distribution. Inspired by this insight, we propose an attention-steerable contrastive decoding framework that directly intervenes in attention mechanisms of the model to offer a more principled approach to mitigating hallucinations. Our experiments across multiple MLLM architectures and diverse decoding methods demonstrate that our approach significantly reduces hallucinations and improves the performance on benchmarks such as POPE, CHAIR, and MMHal-Bench, while simultaneously enhancing performance on standard VQA benchmarks.

[Arxiv](https://arxiv.org/abs/2506.14766)