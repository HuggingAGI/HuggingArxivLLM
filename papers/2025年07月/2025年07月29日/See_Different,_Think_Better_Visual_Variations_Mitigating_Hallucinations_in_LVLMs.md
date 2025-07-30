# 视觉变异助力LVLM：看见不同，思考更佳

发布时间：2025年07月29日

`LLM应用

理由：这篇论文讨论了大型视觉语言模型（LVLMs）中的幻觉现象，并提出了一种基于视觉的框架来缓解这一问题。虽然涉及模型的改进和应用，但主要关注的是模型的应用层面，而非其理论基础。因此，归类为LLM应用。` `计算机视觉`

> See Different, Think Better: Visual Variations Mitigating Hallucinations in LVLMs

# 摘要

> 大型视觉语言模型（LVLMs）在视觉理解和多模态推理方面表现突出，但常出现幻觉现象，即生成文本与视觉内容不一致。现有方法以文本为中心，难以应对细粒度视觉理解中的视觉-语义对齐挑战。为此，我们提出ViHallu，一种基于视觉的幻觉缓解框架，通过“视觉变异图像生成”和“视觉指令构建”增强对齐。ViHallu生成可控变化的视觉变异图像，结合精心设计的指令，帮助模型通过微调更精准地理解视觉内容，提升对齐效果。实验表明，ViHallu显著增强了细粒度视觉理解，减少了幻觉倾向。我们还发布了ViHallu-Instruction数据集，专为幻觉缓解和对齐设计。代码已开源：https://github.com/oliviadzy/ViHallu。

> Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities in visual understanding and multimodal reasoning. However, LVLMs frequently exhibit hallucination phenomena, manifesting as the generated textual responses that demonstrate inconsistencies with the provided visual content. Existing hallucination mitigation methods are predominantly text-centric, the challenges of visual-semantic alignment significantly limit their effectiveness, especially when confronted with fine-grained visual understanding scenarios. To this end, this paper presents ViHallu, a Vision-Centric Hallucination mitigation framework that enhances visual-semantic alignment through Visual Variation Image Generation and Visual Instruction Construction. ViHallu introduces \textbf{\textit{visual variation images}} with controllable visual alterations while maintaining the overall image structure. These images, combined with carefully constructed visual instructions, enable LVLMs to better understand fine-grained visual content through fine-tuning, allowing models to more precisely capture the correspondence between visual content and text, thereby enhancing visual-semantic alignment. Extensive experiments on multiple benchmarks show that ViHallu effectively enhances models' fine-grained visual understanding while significantly reducing hallucination tendencies. Furthermore, we release ViHallu-Instruction, a visual instruction dataset specifically designed for hallucination mitigation and visual-semantic alignment. Code is available at https://github.com/oliviadzy/ViHallu.

[Arxiv](https://arxiv.org/abs/2507.22003)