# 用于文本到图像生成的快速提示对齐

发布时间：2024年12月11日

`LLM应用` `图像生成` `文本处理`

> Fast Prompt Alignment for Text-to-Image Generation

# 摘要

> 文本到图像的生成进步飞快，然而让复杂的文本提示与生成的视觉效果精准匹配仍困难重重，尤其在复杂的对象关系和精细的细节方面。本文引入了快速提示对齐（FPA），这是一种提示优化框架，它借助单程方式，在避免像 OPT2I 等现有方法的迭代开销的情况下，提升了文本到图像的对齐效率。FPA 利用大型语言模型（LLMs）进行单次迭代的提示改写，接着通过优化后的提示进行微调或上下文学习，从而实现实时推理，既降低了计算需求，又保证了对齐的保真度。在 COCO Captions 和 PartiPrompts 数据集上的大量评估显示，FPA 仅用少量的处理时间就获得了颇具竞争力的文本 - 图像对齐分数，这通过自动指标（TIFA，VQA）和人工评估得以证实。有专家注释者参与的人工研究进一步表明，人类的对齐判断与自动得分之间存在很强的相关性，凸显了 FPA 改进的稳健性。所提出的方法呈现出一种可扩展、高效的迭代提示优化替代方案，在实时、高需求的场景中具备更广泛的适用性。代码库已提供，链接为：https://github.com/tiktok/fast_prompt_alignment ，以助力进一步的研究。

> Text-to-image generation has advanced rapidly, yet aligning complex textual prompts with generated visuals remains challenging, especially with intricate object relationships and fine-grained details. This paper introduces Fast Prompt Alignment (FPA), a prompt optimization framework that leverages a one-pass approach, enhancing text-to-image alignment efficiency without the iterative overhead typical of current methods like OPT2I. FPA uses large language models (LLMs) for single-iteration prompt paraphrasing, followed by fine-tuning or in-context learning with optimized prompts to enable real-time inference, reducing computational demands while preserving alignment fidelity. Extensive evaluations on the COCO Captions and PartiPrompts datasets demonstrate that FPA achieves competitive text-image alignment scores at a fraction of the processing time, as validated through both automated metrics (TIFA, VQA) and human evaluation. A human study with expert annotators further reveals a strong correlation between human alignment judgments and automated scores, underscoring the robustness of FPA's improvements. The proposed method showcases a scalable, efficient alternative to iterative prompt optimization, enabling broader applicability in real-time, high-demand settings. The codebase is provided to facilitate further research: https://github.com/tiktok/fast_prompt_alignment

[Arxiv](https://arxiv.org/abs/2412.08639)