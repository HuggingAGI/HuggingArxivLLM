# HiMix: 简化大型视觉-语言模型的计算复杂度

发布时间：2025年01月17日

`LLM应用

理由：这篇论文主要讨论了如何通过创新的分层视觉-语言交互机制（HiMix）来降低大型视觉-语言模型（LVLMs）的计算复杂性，从而提高其实际应用的可行性。虽然论文涉及多模态对齐技术和大型语言模型，但其核心关注点是如何优化这些模型的计算效率，使其更适合实际应用场景。因此，这篇论文应归类为LLM应用。` `计算机视觉`

> HiMix: Reducing Computational Complexity in Large Vision-Language Models

# 摘要

> 得益于大型语言模型和多模态对齐技术的突破，现有的大型视觉-语言模型（LVLMs）在多种场景中表现卓越。然而，高昂的计算成本限制了这些模型的实际应用。我们认为，计算复杂性的主要瓶颈在于模型计算中冗余视觉序列的参与。这一观点源于对LVLMs语言解码器中视觉与语言信息传输效率的重新审视。为此，我们提出了一种创新的分层视觉-语言交互机制——分层视觉注入混合注意力（HiMix）。在HiMix中，语言序列进行完整的正向传播，而视觉序列仅在语言解码器层的特定阶段与语言序列交互。令人惊喜的是，该方法在显著降低计算复杂性的同时，性能损失微乎其微。具体而言，HiMix在多个LVLM模型中实现了语言解码器计算成本10倍的降低，同时保持了可比的性能。这充分展示了我们方法的优势，我们期待这一研究能为视觉-语言理解领域带来新的启发。项目页面：https://xuange923.github.io/HiMix

> Benefiting from recent advancements in large language models and modality alignment techniques, existing Large Vision-Language Models(LVLMs) have achieved prominent performance across a wide range of scenarios. However, the excessive computational complexity limits the widespread use of these models in practical applications. We argue that one main bottleneck in computational complexity is caused by the involvement of redundant vision sequences in model computation. This is inspired by a reassessment of the efficiency of vision and language information transmission in the language decoder of LVLMs. Then, we propose a novel hierarchical vision-language interaction mechanism called Hierarchical Vision injection for Mixture Attention (HiMix). In HiMix, only the language sequence undergoes full forward propagation, while the vision sequence interacts with the language at specific stages within each language decoder layer. It is striking that our approach significantly reduces computational complexity with minimal performance loss. Specifically, HiMix achieves a 10x reduction in the computational cost of the language decoder across multiple LVLM models while maintaining comparable performance. This highlights the advantages of our method, and we hope our research brings new perspectives to the field of vision-language understanding. Project Page: https://xuange923.github.io/HiMix

[Arxiv](https://arxiv.org/abs/2501.10318)