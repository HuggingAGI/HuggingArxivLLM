# 在复杂场景中，利用检索增强标签提升大型视觉-语言理解能力

发布时间：2024年12月15日

`RAG

理由：该论文提出了一个名为视觉感知检索增强提示（VRAP）的框架，通过将检索增强的对象标签融入提示中，提升了大型视觉-语言模型（LVLMs）的能力。这种方法结合了检索增强生成（Retrieval-Augmented Generation, RAG）的思想，即通过外部知识增强模型的输入，从而实现更精准的推理。因此，该论文应归类为RAG。` `计算机视觉`

> Leveraging Retrieval-Augmented Tags for Large Vision-Language Understanding in Complex Scenes

# 摘要

> # 摘要
视觉-语言任务中的对象感知推理对现有模型提出了巨大挑战，尤其是在处理未见对象、减少幻觉以及捕捉复杂场景中的细粒度关系方面。为此，我们提出了视觉感知检索增强提示（VRAP）框架，通过将检索增强的对象标签融入提示中，显著提升了大型视觉-语言模型（LVLMs）的能力。VRAP采用了一种创新流程，利用预训练的视觉编码器和场景图解析器提取对象、属性及关系等结构化标签，并通过外部知识丰富这些标签，最终将其整合到LLM的输入中，实现精准推理。我们在VQAv2、GQA、VizWiz和COCO等多个视觉-语言基准测试中验证了VRAP，其在细粒度推理和多模态理解方面表现卓越。消融实验进一步证明了检索增强标签和对比学习的关键作用，而人类评估则表明VRAP能够生成准确、详细且上下文相关的响应。值得一提的是，VRAP通过消除运行时检索，将推理延迟降低了40%。这些成果表明，VRAP是一个高效且强大的框架，能够显著提升对象感知的多模态推理能力。

> Object-aware reasoning in vision-language tasks poses significant challenges for current models, particularly in handling unseen objects, reducing hallucinations, and capturing fine-grained relationships in complex visual scenes. To address these limitations, we propose the Vision-Aware Retrieval-Augmented Prompting (VRAP) framework, a generative approach that enhances Large Vision-Language Models (LVLMs) by integrating retrieval-augmented object tags into their prompts. VRAP introduces a novel pipeline where structured tags, including objects, attributes, and relationships, are extracted using pretrained visual encoders and scene graph parsers. These tags are enriched with external knowledge and incorporated into the LLM's input, enabling detailed and accurate reasoning. We evaluate VRAP across multiple vision-language benchmarks, including VQAv2, GQA, VizWiz, and COCO, achieving state-of-the-art performance in fine-grained reasoning and multimodal understanding. Additionally, our ablation studies highlight the importance of retrieval-augmented tags and contrastive learning, while human evaluations confirm VRAP's ability to generate accurate, detailed, and contextually relevant responses. Notably, VRAP achieves a 40% reduction in inference latency by eliminating runtime retrieval. These results demonstrate that VRAP is a robust and efficient framework for advancing object-aware multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2412.11396)