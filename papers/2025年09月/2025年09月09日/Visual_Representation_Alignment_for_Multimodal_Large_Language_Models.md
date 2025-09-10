# # 多模态大型语言模型的视觉表征对齐

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Visual Representation Alignment for Multimodal Large Language Models

# 摘要

> 经过视觉指令微调的多模态大型语言模型（MLLMs）虽在各类任务中表现优异，却在目标计数、空间推理等视觉核心任务上仍有局限。我们认为，这一短板源于主流的纯文本监督模式——它仅能为视觉通路提供间接引导，还容易使MLLMs在训练时丢失细粒度视觉细节。本文提出视觉表征对齐（VIRAL）——一种简洁高效的正则化策略，可将MLLMs的内部视觉表征与预训练视觉基础模型（VFMs）的表征对齐。通过显式强化这种对齐，VIRAL既能让模型保留输入视觉编码器的关键视觉细节，又能补充VFMs的额外视觉知识，进而提升对复杂视觉输入的推理能力。实验结果显示，在主流多模态基准的各项任务中，模型性能均有稳定提升。此外，我们通过全面的消融实验验证了框架核心设计的合理性。我们相信，这一简洁发现为MLLMs训练中视觉信息的有效融合开辟了重要方向。

> Multimodal large language models (MLLMs) trained with visual instruction tuning have achieved strong performance across diverse tasks, yet they remain limited in vision-centric tasks such as object counting or spatial reasoning. We attribute this gap to the prevailing text-only supervision paradigm, which provides only indirect guidance for the visual pathway and often leads MLLMs to discard fine-grained visual details during training. In this paper, we present VIsual Representation ALignment (VIRAL), a simple yet effective regularization strategy that aligns the internal visual representations of MLLMs with those of pre-trained vision foundation models (VFMs). By explicitly enforcing this alignment, VIRAL enables the model not only to retain critical visual details from the input vision encoder but also to complement additional visual knowledge from VFMs, thereby enhancing its ability to reason over complex visual inputs. Our experiments demonstrate consistent improvements across all tasks on widely adopted multimodal benchmarks. Furthermore, we conduct comprehensive ablation studies to validate the key design choices underlying our framework. We believe this simple finding opens up an important direction for the effective integration of visual information in training MLLMs.

[Arxiv](https://arxiv.org/abs/2509.07979)