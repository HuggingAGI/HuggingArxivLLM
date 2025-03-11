# VisualSimpleQA：评估大型视觉-语言模型在事实查询问答任务中独立性能的基准测试。

发布时间：2025年03月09日

`LLM应用` `计算机视觉`

> VisualSimpleQA: A Benchmark for Decoupled Evaluation of Large Vision-Language Models in Fact-Seeking Question Answering

# 摘要

> 尽管大型视觉语言模型（LVLMs）取得了令人瞩目的成就，但事实检索型问答（QA）中仍普遍出现非事实性回答。现有研究多聚焦于对比模型输出与真实答案，对视觉与语言模态模块的性能分析却十分有限。为此，我们推出了VisualSimpleQA，一个多模态事实检索基准测试，具有两大创新特性：首先，它支持对LVLMs在视觉和语言模态上的独立评估；其次，通过明确的难度标准指导人工标注，并提取更具挑战性的子集——VisualSimpleQA-hard。实验结果显示，即便是GPT-4o等顶尖模型，在VisualSimpleQA上的正确率也仅为60%+，而在VisualSimpleQA-hard上更是低至30%+。这一发现表明，视觉与语言模块均存在显著的提升空间。数据集已开放获取，链接为https://huggingface.co/datasets/WYLing/VisualSimpleQA。

> Large vision-language models (LVLMs) have demonstrated remarkable achievements, yet the generation of non-factual responses remains prevalent in fact-seeking question answering (QA). Current multimodal fact-seeking benchmarks primarily focus on comparing model outputs to ground truth answers, providing limited insights into the performance of modality-specific modules. To bridge this gap, we introduce VisualSimpleQA, a multimodal fact-seeking benchmark with two key features. First, it enables streamlined and decoupled evaluation of LVLMs in visual and linguistic modalities. Second, it incorporates well-defined difficulty criteria to guide human annotation and facilitates the extraction of a challenging subset, VisualSimpleQA-hard. Experiments on 15 LVLMs show that even state-of-the-art models such as GPT-4o achieve merely 60%+ correctness in multimodal fact-seeking QA on VisualSimpleQA and 30%+ on VisualSimpleQA-hard. Furthermore, the decoupled evaluation across these models highlights substantial opportunities for improvement in both visual and linguistic modules. The dataset is available at https://huggingface.co/datasets/WYLing/VisualSimpleQA.

[Arxiv](https://arxiv.org/abs/2503.06492)