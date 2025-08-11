# 遵循您的指令：一个全面的多语言大语言模型代理用于全球数据整合

发布时间：2025年08月07日

`LLM应用` `生成智能`

> Follow-Your-Instruction: A Comprehensive MLLM Agent for World Data Synthesis

# 摘要

> 随着AI生成内容（AIGC）需求的激增，高质量、多样化且可扩展的数据已成为推动发展的关键。然而，大规模真实数据的收集依然面临成本高昂和耗时的挑战，严重制约了下游应用的进展。尽管部分研究尝试通过渲染技术收集特定任务数据，但大多数方法仍依赖于手动构建场景，这不仅限制了可扩展性，也影响了数据准确性。为突破这些限制，我们提出了一种基于多模态大语言模型（MLLM）的创新框架——	extbf{Follow-Your-Instruction}，用于自动合成高质量的2D、3D和4D数据。该框架首先通过MLLM-Collector收集多模态资产及其描述，随后利用MLLM-Generator和MLLM-Optimizer构建3D布局并借助视觉-语言模型（VLM）进行多视图语义优化，最后借助MLLM-Planner生成时间连贯的未来帧。通过在2D、3D和4D生成任务上的全面实验，我们验证了合成数据的卓越质量。结果显示，该框架显著提升了现有基线模型的性能，充分展现了其作为生成智能领域高效数据引擎的潜力。

> With the growing demands of AI-generated content (AIGC), the need for high-quality, diverse, and scalable data has become increasingly crucial. However, collecting large-scale real-world data remains costly and time-consuming, hindering the development of downstream applications. While some works attempt to collect task-specific data via a rendering process, most approaches still rely on manual scene construction, limiting their scalability and accuracy. To address these challenges, we propose Follow-Your-Instruction, a Multimodal Large Language Model (MLLM)-driven framework for automatically synthesizing high-quality 2D, 3D, and 4D data. Our \textbf{Follow-Your-Instruction} first collects assets and their associated descriptions through multimodal inputs using the MLLM-Collector. Then it constructs 3D layouts, and leverages Vision-Language Models (VLMs) for semantic refinement through multi-view scenes with the MLLM-Generator and MLLM-Optimizer, respectively. Finally, it uses MLLM-Planner to generate temporally coherent future frames. We evaluate the quality of the generated data through comprehensive experiments on the 2D, 3D, and 4D generative tasks. The results show that our synthetic data significantly boosts the performance of existing baseline models, demonstrating Follow-Your-Instruction's potential as a scalable and effective data engine for generative intelligence.

[Arxiv](https://arxiv.org/abs/2508.05580)