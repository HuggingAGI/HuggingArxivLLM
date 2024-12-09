# CompCap：利用复合标题提升多模态大型语言模型

发布时间：2024年12月06日

`LLM应用` `语言模型`

> CompCap: Improving Multimodal Large Language Models with Composite Captions

# 摘要

> 多模态大型语言模型（MLLMs）对合成图像的理解水平怎样？合成图像（CIs）是由多个视觉元素（像图表、海报或者屏幕截图）融合而成的合成视觉产物，并非直接由相机拍摄所得。尽管 CIs 在实际应用中颇为常见，但近期 MLLM 的发展重点主要放在对自然图像（NIs）的解读上。我们的研究显示，当下的 MLLMs 在准确理解 CIs 时面临着巨大挑战，往往难以依据这些图像提取信息或者进行复杂推理。我们发现，现有的 CIs 训练数据大多是为问答任务而设定的格式（比如在 ChartQA 和 ScienceQA 等数据集中），而对强大的视觉语言对齐至关重要的高质量图像字幕数据集仅面向 NIs。为了填补这一空缺，我们引入了复合字幕（CompCap），这是一个灵活的框架，借助大型语言模型（LLMs）和自动化工具来合成带有准确且详尽字幕的 CIs。通过使用 CompCap，我们整理出了 CompCap-118K，这是一个涵盖六种 CI 类型、包含 118K 个图像字幕对的数据集。我们通过对三种规模的 MLLMs（xGen-MM-inst.-4B 和 LLaVA-NeXT-Vicuna-7B/13B）进行有监督的微调，验证了 CompCap-118K 的有效性。实证结果表明，CompCap-118K 显著提升了 MLLMs 对 CIs 的理解能力，在十一个基准测试中分别平均提升了 1.7％、2.0％和 2.9％。

> How well can Multimodal Large Language Models (MLLMs) understand composite images? Composite images (CIs) are synthetic visuals created by merging multiple visual elements, such as charts, posters, or screenshots, rather than being captured directly by a camera. While CIs are prevalent in real-world applications, recent MLLM developments have primarily focused on interpreting natural images (NIs). Our research reveals that current MLLMs face significant challenges in accurately understanding CIs, often struggling to extract information or perform complex reasoning based on these images. We find that existing training data for CIs are mostly formatted for question-answer tasks (e.g., in datasets like ChartQA and ScienceQA), while high-quality image-caption datasets, critical for robust vision-language alignment, are only available for NIs. To bridge this gap, we introduce Composite Captions (CompCap), a flexible framework that leverages Large Language Models (LLMs) and automation tools to synthesize CIs with accurate and detailed captions. Using CompCap, we curate CompCap-118K, a dataset containing 118K image-caption pairs across six CI types. We validate the effectiveness of CompCap-118K by supervised fine-tuning MLLMs of three sizes: xGen-MM-inst.-4B and LLaVA-NeXT-Vicuna-7B/13B. Empirical results show that CompCap-118K significantly enhances MLLMs' understanding of CIs, yielding average gains of 1.7%, 2.0%, and 2.9% across eleven benchmarks, respectively.

[Arxiv](https://arxiv.org/abs/2412.05243)