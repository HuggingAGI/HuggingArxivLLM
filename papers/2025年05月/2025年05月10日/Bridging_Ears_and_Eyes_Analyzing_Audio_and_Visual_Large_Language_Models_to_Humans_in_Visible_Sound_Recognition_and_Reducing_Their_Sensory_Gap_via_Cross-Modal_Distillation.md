# # 连接听觉与视觉：分析音频-视觉大型语言模型如何模拟人类的感知能力，并通过跨模态蒸馏缩小感知差距

发布时间：2025年05月10日

`LLM应用

理由：这篇论文探讨了音频大语言模型（LLMs）在声音识别中的应用，并将其与视觉和视听模型进行对比。研究者提出了一种跨模态蒸馏框架，以提升模型在不同声音类别上的性能。这属于LLM的应用层面，特别是跨模态学习和模型性能提升的实践。` `音频处理` `人工智能`

> Bridging Ears and Eyes: Analyzing Audio and Visual Large Language Models to Humans in Visible Sound Recognition and Reducing Their Sensory Gap via Cross-Modal Distillation

# 摘要

> 音频大语言模型（LLMs）在声音识别领域表现卓越，但其与视觉或视听LLMs等其他感官模态模型，以及人类使用耳朵、眼睛或两者结合的能力相比，仍有待探索。我们系统评估了Qwen2-Audio、Qwen2-VL和Qwen2.5-Omni等音频、视觉和视听模型，与人类在识别不同声音类别上的表现进行对比。我们发现Qwen2-Audio与Qwen2-VL之间的性能差距与人类耳朵与眼睛的感官差异相平行。为缩小这一差距，我们提出了一种跨模态蒸馏框架，其中一种模态的LLM作为教师，另一种作为学生，通过启发式模型预测更具挑战性的声音类别实现知识转移。双向蒸馏（从Qwen2-VL到Qwen2-Audio及反之）显著提升了模型性能，尤其在具有挑战性的类别中。这项研究从与人类感知对齐的角度揭示了LLMs的感官差距，并提出了一种增强多模态LLMs特定模态感知的系统性方法。

> Audio large language models (LLMs) are considered experts at recognizing sound objects, yet their performance relative to LLMs in other sensory modalities, such as visual or audio-visual LLMs, and to humans using their ears, eyes, or both remains unexplored. To investigate this, we systematically evaluate audio, visual, and audio-visual LLMs, specifically Qwen2-Audio, Qwen2-VL, and Qwen2.5-Omni, against humans in recognizing sound objects of different classes from audio-only, silent video, or sounded video inputs. We uncover a performance gap between Qwen2-Audio and Qwen2-VL that parallels the sensory discrepancy between human ears and eyes. To reduce this gap, we introduce a cross-modal distillation framework, where an LLM in one modality serves as the teacher and another as the student, with knowledge transfer in sound classes predicted as more challenging to the student by a heuristic model. Distillation in both directions, from Qwen2-VL to Qwen2-Audio and vice versa, leads to notable improvements, particularly in challenging classes. This work highlights the sensory gap in LLMs from a human-aligned perspective and proposes a principled approach to enhancing modality-specific perception in multimodal LLMs.

[Arxiv](https://arxiv.org/abs/2505.06803)