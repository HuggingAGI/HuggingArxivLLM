# CAFe：对比自回归微调，统一表示与生成

发布时间：2025年03月25日

`其他

理由：这篇论文探讨了大型视觉-语言模型（LVLMs）在多模态任务中的应用，提出了一种新的微调框架CAFe，结合对比学习和自回归建模，以提升模型的表示和生成能力。由于其专注于多模态模型而非纯语言模型，且不涉及智能体或检索增强生成，因此归类为其他。` `多模态` `视觉-语言模型`

> CAFe: Unifying Representation and Generation with Contrastive-Autoregressive Finetuning

# 摘要

> 大型视觉-语言模型（LVLMs）的快速发展显著推动了多模态任务的进步，使其能够跨视觉与文本领域进行解释、推理和生成。尽管在生成任务中表现出色，但现有模型在需要高保真表示学习的任务中仍存在局限，例如生成用于检索的图像或文本嵌入。近期研究尝试通过微调LVLMs来提升表示学习能力，但这一过程往往导致模型失去生成能力。为解决这一权衡问题，我们提出了CAFe——一个对比-自回归微调框架，旨在同时提升模型在表示和生成任务中的性能。通过将对比目标与自回归语言建模相结合，CAFe统一了这两个传统上分离的任务，在多模态检索和生成基准测试中取得了领先结果，包括物体幻觉（OH）缓解。CAFe不仅建立了一个协同整合嵌入与生成功能的新型框架，更为未来多模态模型在检索精度与连贯输出生成方面均达到卓越表现奠定了基础。

> The rapid advancement of large vision-language models (LVLMs) has driven significant progress in multimodal tasks, enabling models to interpret, reason, and generate outputs across both visual and textual domains. While excelling in generative tasks, existing LVLMs often face limitations in tasks requiring high-fidelity representation learning, such as generating image or text embeddings for retrieval. Recent work has proposed finetuning LVLMs for representational learning, but the fine-tuned model often loses its generative capabilities due to the representational learning training paradigm. To address this trade-off, we introduce CAFe, a contrastive-autoregressive fine-tuning framework that enhances LVLMs for both representation and generative tasks. By integrating a contrastive objective with autoregressive language modeling, our approach unifies these traditionally separate tasks, achieving state-of-the-art results in both multimodal retrieval and multimodal generative benchmarks, including object hallucination (OH) mitigation. CAFe establishes a novel framework that synergizes embedding and generative functionalities in a single model, setting a foundation for future multimodal models that excel in both retrieval precision and coherent output generation.

[Arxiv](https://arxiv.org/abs/2503.19900)