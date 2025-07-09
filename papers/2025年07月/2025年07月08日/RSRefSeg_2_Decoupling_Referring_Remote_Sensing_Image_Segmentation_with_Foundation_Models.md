# RSRefSeg 2：基于基础模型的引用遥感图像分割解耦方法

发布时间：2025年07月08日

`LLM应用` `图像分割`

> RSRefSeg 2: Decoupling Referring Remote Sensing Image Segmentation with Foundation Models

# 摘要

> 引用遥感图像分割通过视觉-语言协作解释为遥感场景分析提供了一个灵活且精细的框架。当前方法主要采用一个包含双模态编码、跨模态交互和像素解码的三阶段流水线方法，但这些方法在处理复杂语义关系和实现精确跨模态对齐方面存在显著局限性。这主要是因为它们的处理机制将目标定位与边界划分混为一谈，这种架构上的耦合在语义模糊情况下加剧了误差传播，同时限制了模型的泛化能力和可解释性。

为了解决这些问题，我们提出了RSRefSeg 2，这是一种解耦范式，将传统的三阶段工作流重新设计为协作式的双阶段框架：首先进行粗略定位，然后进行精细分割。RSRefSeg 2通过战略性地协作基础模型，将CLIP的跨模态对齐优势与SAM的分割泛化能力相结合。具体来说，CLIP被用作双模态编码器，在其预对齐的语义空间中激活目标特征并生成定位提示。

为了缓解CLIP在多实体场景中由引用文本描述带来的误激活问题，我们设计了一个级联的二阶提示器，通过分解文本嵌入到互补的语义子空间中，增强了隐式推理，从而提高精度。这些优化后的语义提示随后引导SAM生成像素级细化的掩膜，从而完成语义传递管道。

大量实验（RefSegRS、RRSIS-D 和 RISBench）表明，RSRefSeg 2在分割精度（+~3% gIoU）和复杂语义解释方面优于现有方法。代码可在以下链接获取：https://github.com/KyanChen/RSRefSeg2。


> Referring Remote Sensing Image Segmentation provides a flexible and fine-grained framework for remote sensing scene analysis via vision-language collaborative interpretation. Current approaches predominantly utilize a three-stage pipeline encompassing dual-modal encoding, cross-modal interaction, and pixel decoding. These methods demonstrate significant limitations in managing complex semantic relationships and achieving precise cross-modal alignment, largely due to their coupled processing mechanism that conflates target localization with boundary delineation. This architectural coupling amplifies error propagation under semantic ambiguity while restricting model generalizability and interpretability. To address these issues, we propose RSRefSeg 2, a decoupling paradigm that reformulates the conventional workflow into a collaborative dual-stage framework: coarse localization followed by fine segmentation. RSRefSeg 2 integrates CLIP's cross-modal alignment strength with SAM's segmentation generalizability through strategic foundation model collaboration. Specifically, CLIP is employed as the dual-modal encoder to activate target features within its pre-aligned semantic space and generate localization prompts. To mitigate CLIP's misactivation challenges in multi-entity scenarios described by referring texts, a cascaded second-order prompter is devised, which enhances precision through implicit reasoning via decomposition of text embeddings into complementary semantic subspaces. These optimized semantic prompts subsequently direct the SAM to generate pixel-level refined masks, thereby completing the semantic transmission pipeline. Extensive experiments (RefSegRS, RRSIS-D, and RISBench) demonstrate that RSRefSeg 2 surpasses contemporary methods in segmentation accuracy (+~3% gIoU) and complex semantic interpretation. Code is available at: https://github.com/KyanChen/RSRefSeg2.

[Arxiv](https://arxiv.org/abs/2507.06231)