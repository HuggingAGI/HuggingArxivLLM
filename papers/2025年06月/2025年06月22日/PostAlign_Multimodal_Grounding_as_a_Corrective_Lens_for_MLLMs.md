# PostAlign：为多模态大语言模型提供矫正视角的多模态对齐方法

发布时间：2025年06月22日

`LLM应用` `计算机视觉` `多模态模型`

> PostAlign: Multimodal Grounding as a Corrective Lens for MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在图像描述和视觉问答等任务中表现出色，但常因过度依赖语言先验而忽视实际视觉信息。我们提出MMGrounded-PostAlign框架，通过多模态定位模块提升模型的视觉理解并减少幻觉。该模块包含视觉定位和文本定位功能，确保输出基于可靠证据。我们还引入负向拒绝机制和选择性推理机制，有效抑制幻觉现象。在多个基准测试中，我们的框架在细粒度视觉理解和幻觉抑制方面表现优异。

> Multimodal Large Language Models (MLLMs) excel in vision-language tasks, such as image captioning and visual question answering. However, they often suffer from over-reliance on spurious correlations, primarily due to linguistic priors that distract the model from leveraging actual visual information. To address these issues, we introduce MMGrounded-PostAlign, a post-multimodal alignment framework designed to enhance the visual understanding capabilities and mitigate the hallucinations of MLLMs. Our framework incorporates a multimodal grounding module for both visual grounding, which identifies the referred object in the image, and textual grounding, which generates the rationale for the final answer, ensuring that outputs are anchored in both visual and textual evidence. To mitigate the hallucinations, we introduce a negative rejection mechanism in the visual grounding module to distinguish grounded entities from non-existent objects influenced by linguistic biases. On the textual grounding side, we propose a selective reasoning mechanism that adjusts the model's reasoning strategy based on query complexity. Extensive evaluations are conducted on benchmarks such as POPE, HaloQuest, VQAv2, MME, and MMBench showing significant improvements in fine-grained visual understanding and hallucination suppression.

[Arxiv](https://arxiv.org/abs/2506.17901)