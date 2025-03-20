# 通用场景图生成

发布时间：2025年03月19日

`其他` `多模态处理` `计算机视觉`

> Universal Scene Graph Generation

# 摘要

> 场景图（SG）表示能够简洁高效地描述场景语义，推动了持续深入的SG生成研究。现实中，图像、文本、视频和3D数据等多模态信息常常共存，各自展现独特特征。然而，当前SG研究主要局限于单一模态场景建模，未能充分利用不同模态SG表示的互补优势来全面描绘场景语义。为此，我们提出了通用场景图（USG），一种能够全面刻画任意模态输入组合所呈现的综合性语义场景的新型表示方法，涵盖跨模态通用场景和特定模态场景。同时，我们开发了专门针对USG的解析器USG-Par，有效解决了跨模态对象对齐和跨领域挑战两大关键难题。USG-Par采用模块化架构设计，实现端到端的USG生成。其中，我们设计了对象关联器来缓解跨模态对象对齐中的模态差异问题。此外，我们提出了一种以文本为中心的场景对比学习机制，通过将多模态对象和关系与文本SG对齐，有效缓解领域不平衡问题。通过大量实验验证，USG在表达场景语义方面的能力优于独立的SG，而我们的USG-Par也展现出更高的效能和性能表现。

> Scene graph (SG) representations can neatly and efficiently describe scene semantics, which has driven sustained intensive research in SG generation. In the real world, multiple modalities often coexist, with different types, such as images, text, video, and 3D data, expressing distinct characteristics. Unfortunately, current SG research is largely confined to single-modality scene modeling, preventing the full utilization of the complementary strengths of different modality SG representations in depicting holistic scene semantics. To this end, we introduce Universal SG (USG), a novel representation capable of fully characterizing comprehensive semantic scenes from any given combination of modality inputs, encompassing modality-invariant and modality-specific scenes. Further, we tailor a niche-targeting USG parser, USG-Par, which effectively addresses two key bottlenecks of cross-modal object alignment and out-of-domain challenges. We design the USG-Par with modular architecture for end-to-end USG generation, in which we devise an object associator to relieve the modality gap for cross-modal object alignment. Further, we propose a text-centric scene contrasting learning mechanism to mitigate domain imbalances by aligning multimodal objects and relations with textual SGs. Through extensive experiments, we demonstrate that USG offers a stronger capability for expressing scene semantics than standalone SGs, and also that our USG-Par achieves higher efficacy and performance.

[Arxiv](https://arxiv.org/abs/2503.15005)