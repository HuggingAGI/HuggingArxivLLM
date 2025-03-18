# # MicroVQA：显微科学多模态推理基准

发布时间：2025年03月17日

`LLM应用` `生物医学` `科学研究`

> MicroVQA: A Multimodal Reasoning Benchmark for Microscopy-Based Scientific Research

# 摘要

> 科学研究中的多模态推理挑战，尤其是生物学领域，亟待解决。尽管多模态大型语言模型（MLLMs）在AI辅助研究中取得了进展，现有基准测试要么难度不足，要么仅关注低级感知，无法满足科学研究的需求。为此，我们推出了MicroVQA，一个视觉问答（VQA）基准，专注于评估专家级图像理解、假设生成和实验提案这三大科研核心能力。MicroVQA包含1,042个由生物学专家整理的多项选择题（MCQs），覆盖多种显微镜模态，确保问题贴近真实科研场景。

在构建过程中，我们发现传统MCQ生成方法存在语言捷径问题，因此创新性地提出了两阶段管道：优化的LLM提示生成问答对，再由基于代理的`RefineBot`进行优化以消除捷径。在先进MLLMs上的测试显示，峰值性能达到53%。有趣的是，使用较小规模LLM的模型表现仅稍逊，表明语言推理难度低于多模态推理；而通过科学文章微调可显著提升性能。专家分析显示，感知错误最常见，其次是知识错误和过度概括错误。这些发现凸显了多模态科学推理的复杂性，也证明MicroVQA是推动AI驱动生物医学研究的宝贵资源。MicroVQA现已在Hugging Face平台上线（https://huggingface.co/datasets/jmhb/microvqa），更多信息请访问项目页面（https://jmhb0.github.io/microvqa）。


> Scientific research demands sophisticated reasoning over multimodal data, a challenge especially prevalent in biology. Despite recent advances in multimodal large language models (MLLMs) for AI-assisted research, existing multimodal reasoning benchmarks only target up to college-level difficulty, while research-level benchmarks emphasize lower-level perception, falling short of the complex multimodal reasoning needed for scientific discovery. To bridge this gap, we introduce MicroVQA, a visual-question answering (VQA) benchmark designed to assess three reasoning capabilities vital in research workflows: expert image understanding, hypothesis generation, and experiment proposal. MicroVQA consists of 1,042 multiple-choice questions (MCQs) curated by biology experts across diverse microscopy modalities, ensuring VQA samples represent real scientific practice. In constructing the benchmark, we find that standard MCQ generation methods induce language shortcuts, motivating a new two-stage pipeline: an optimized LLM prompt structures question-answer pairs into MCQs; then, an agent-based `RefineBot' updates them to remove shortcuts. Benchmarking on state-of-the-art MLLMs reveal a peak performance of 53\%; models with smaller LLMs only slightly underperform top models, suggesting that language-based reasoning is less challenging than multimodal reasoning; and tuning with scientific articles enhances performance. Expert analysis of chain-of-thought responses shows that perception errors are the most frequent, followed by knowledge errors and then overgeneralization errors. These insights highlight the challenges in multimodal scientific reasoning, showing MicroVQA is a valuable resource advancing AI-driven biomedical research. MicroVQA is available at https://huggingface.co/datasets/jmhb/microvqa, and project page at https://jmhb0.github.io/microvqa.

[Arxiv](https://arxiv.org/abs/2503.13399)