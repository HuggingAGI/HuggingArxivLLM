# 实现视觉空间认知，通过层次化融合视觉专家

发布时间：2025年05月18日

`LLM应用` `计算机视觉` `多模态`

> Towards Visuospatial Cognition via Hierarchical Fusion of Visual Experts

# 摘要

> 尽管多模态大语言模型（MLLMs）在通用视觉语言任务中表现出色，但视觉空间认知——对空间布局、关系和动态的推理——仍然是一个重大挑战。现有模型往往缺乏必要的架构组件和专门的训练数据，难以实现精细的空间理解。我们推出ViCA2（视觉空间认知助手2），一款旨在提升空间推理能力的新型MLLM。ViCA2采用双视觉编码器架构，整合SigLIP用于语义理解和Hiera用于空间结构分析，并配备令牌比例控制机制以优化效率。我们还开发了ViCA-322K，一个包含322,000多个空间关联问答对的新大规模数据集，用于针对性指令微调。在具有挑战性的VSI-Bench基准测试中，我们的ViCA2-7B模型达到56.8的平均分，创下了该领域的最新记录，远超更大规模的开源模型（如LLaVA-NeXT-Video-72B，40.9分）和领先的专有模型（如Gemini-1.5 Pro，45.4分）。这充分证明了我们的方法能够以精简模型实现强大的视觉空间智能。我们已开放ViCA2模型、代码库和ViCA-322K数据集，以推动进一步研究。

> While Multimodal Large Language Models (MLLMs) excel at general vision-language tasks, visuospatial cognition - reasoning about spatial layouts, relations, and dynamics - remains a significant challenge. Existing models often lack the necessary architectural components and specialized training data for fine-grained spatial understanding. We introduce ViCA2 (Visuospatial Cognitive Assistant 2), a novel MLLM designed to enhance spatial reasoning. ViCA2 features a dual vision encoder architecture integrating SigLIP for semantics and Hiera for spatial structure, coupled with a token ratio control mechanism for efficiency. We also developed ViCA-322K, a new large-scale dataset with over 322,000 spatially grounded question-answer pairs for targeted instruction tuning. On the challenging VSI-Bench benchmark, our ViCA2-7B model achieves a state-of-the-art average score of 56.8, significantly surpassing larger open-source models (e.g., LLaVA-NeXT-Video-72B, 40.9) and leading proprietary models (Gemini-1.5 Pro, 45.4). This demonstrates the effectiveness of our approach in achieving strong visuospatial intelligence with a compact model. We release ViCA2, its codebase, and the ViCA-322K dataset to facilitate further research.

[Arxiv](https://arxiv.org/abs/2505.12363)