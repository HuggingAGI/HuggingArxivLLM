# Visual-TableQA：开放域表格图像推理基准

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Visual-TableQA: Open-Domain Benchmark for Reasoning over Table Images

# 摘要

> 对表格等结构化数据的视觉推理是现代视觉语言模型（VLMs）的核心能力，但现有基准测试在规模、多样性或推理深度上仍有局限，尤其是在处理渲染表格图像时。为填补这一空白，我们推出了Visual-TableQA——一个大规模、开放域的多模态数据集，专门用于评估和提升复杂表格数据的视觉推理能力。我们的生成流程模块化、可扩展且完全自动化，由多个推理LLM分工协作，分别承担生成、验证和启发角色。Visual-TableQA包含2500个结构丰富的LaTeX渲染表格和6000个推理密集型问答对，制作成本不到100美元。为提升数据的多样性和创造性，我们的流程通过跨模型提示（‘启发’）和LLM评审团过滤实现多模型协作数据生成：较强模型提供布局和主题种子，较弱模型在此基础上进行细化，共同将多样化的推理模式和视觉结构融入数据集中。实证结果显示，在Visual-TableQA上微调的模型能稳健泛化至外部基准测试，尽管该数据集为合成数据，但其性能仍优于多个专有模型。完整流程及资源已在https://github.com/AI-4-Everyone/Visual-TableQA公开。

> Visual reasoning over structured data such as tables is a critical capability for modern vision-language models (VLMs), yet current benchmarks remain limited in scale, diversity, or reasoning depth, especially when it comes to rendered table images. Addressing this gap, we introduce Visual-TableQA, a large-scale, open-domain multimodal dataset specifically designed to evaluate and enhance visual reasoning over complex tabular data. Our generation pipeline is modular, scalable, and fully autonomous, involving multiple reasoning LLMs collaborating across distinct roles: generation, validation, and inspiration. Visual-TableQA comprises 2.5k richly structured LaTeX-rendered tables and 6k reasoning-intensive QA pairs, all produced at a cost of under USD 100. To promote diversity and creativity, our pipeline performs multi-model collaborative data generation via cross-model prompting ('inspiration') and LLM-jury filtering. Stronger models seed layouts and topics that weaker models elaborate, collectively distilling diverse reasoning patterns and visual structures into the dataset. Empirical results show that models fine-tuned on Visual-TableQA generalize robustly to external benchmarks, outperforming several proprietary models despite the dataset's synthetic nature. The full pipeline and resources are publicly available at https://github.com/AI-4-Everyone/Visual-TableQA.

[Arxiv](https://arxiv.org/abs/2509.07966)