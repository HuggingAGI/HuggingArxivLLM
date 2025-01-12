# 多模态生成任务中基于视觉的大型语言模型提示优化

发布时间：2025年01月05日

`LLM应用

**理由**：该论文提出了一种利用大型语言模型（LLMs）从视觉输入中动态生成文本提示的框架，用于指导高保真图像合成。这属于LLM在实际应用中的使用，特别是结合视觉生成任务，因此应归类为LLM应用。` `计算机视觉` `图像生成`

> Vision-Driven Prompt Optimization for Large Language Models in Multimodal Generative Tasks

# 摘要

> # 摘要
视觉生成是人工智能领域的一大挑战，需要将视觉理解与生成能力无缝结合。本文提出了一种创新框架——视觉驱动的提示优化（VDPO），它利用大型语言模型（LLMs）从视觉输入中动态生成文本提示，从而指导高保真图像合成。VDPO集成了视觉嵌入提示调谐器、文本指令生成器和视觉生成模块，在多种视觉生成任务中表现卓越。在COCO和Sketchy等基准测试中，VDPO持续超越现有方法，显著提升了FID、LPIPS和BLEU/CIDEr分数。进一步分析显示，VDPO具备出色的可扩展性、鲁棒性和泛化能力，适用于各类域内和域外任务。人类评估也证实了VDPO在生成视觉吸引力和语义连贯输出方面的实际优势。

> Vision generation remains a challenging frontier in artificial intelligence, requiring seamless integration of visual understanding and generative capabilities. In this paper, we propose a novel framework, Vision-Driven Prompt Optimization (VDPO), that leverages Large Language Models (LLMs) to dynamically generate textual prompts from visual inputs, guiding high-fidelity image synthesis. VDPO combines a visual embedding prompt tuner, a textual instruction generator, and a vision generation module to achieve state-of-the-art performance in diverse vision generation tasks. Extensive experiments on benchmarks such as COCO and Sketchy demonstrate that VDPO consistently outperforms existing methods, achieving significant improvements in FID, LPIPS, and BLEU/CIDEr scores. Additional analyses reveal the scalability, robustness, and generalization capabilities of VDPO, making it a versatile solution for in-domain and out-of-domain tasks. Human evaluations further validate the practical superiority of VDPO in generating visually appealing and semantically coherent outputs.

[Arxiv](https://arxiv.org/abs/2501.02527)