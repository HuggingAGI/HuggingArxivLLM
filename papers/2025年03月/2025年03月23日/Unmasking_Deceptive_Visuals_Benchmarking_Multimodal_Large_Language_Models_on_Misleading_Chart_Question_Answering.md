# 揭露欺骗性图表：评估多模态大模型在误导性图表问答任务中的表现

发布时间：2025年03月23日

`LLM应用

摘要中提到的多模态大型语言模型（MLLMs）在图表理解中的应用，以及他们开发的Misleading ChartQA基准测试，都是将LLM应用于检测和解读误导性图表的具体实例。因此，这篇论文属于LLM应用类别。` `图表可视化` `信息检测`

> Unmasking Deceptive Visuals: Benchmarking Multimodal Large Language Models on Misleading Chart Question Answering

# 摘要

> 误导性图表可视化通过故意操控数据呈现方式支持特定主张，可能导致认知扭曲和错误结论。尽管经过数十年研究，误导性可视化仍然是一个普遍且紧迫的问题。近期，多模态大型语言模型（MLLMs）在图表理解方面展现出强大能力，但尚未有研究系统评估其检测和解读误导性图表的能力。本文提出了一种误导性图表问答（Misleading ChartQA）基准测试，这是一个大规模多模态数据集，旨在评估MLLMs在识别和推理误导性图表方面的能力。该数据集包含3000多个精选案例，涵盖21种误导手法和10种图表类型。每个案例都包含标准化图表代码、CSV数据以及带有标注解释的多项选择题，经过多轮MLLM检查和专家人工审核验证。我们在数据集上对16个最先进的MLLMs进行了基准测试，揭示了它们在识别视觉欺骗实践方面的局限性。我们还提出了一种新型管道，能够检测和定位误导手法，从而提高了MLLMs对误导性图表的解读准确性。我们的研究为推动MLLM驱动的误导性图表理解奠定了基础。我们公开发布了示例数据集，以支持这一关键领域的进一步研究。

> Misleading chart visualizations, which intentionally manipulate data representations to support specific claims, can distort perceptions and lead to incorrect conclusions. Despite decades of research, misleading visualizations remain a widespread and pressing issue. Recent advances in multimodal large language models (MLLMs) have demonstrated strong chart comprehension capabilities, yet no existing work has systematically evaluated their ability to detect and interpret misleading charts. This paper introduces the Misleading Chart Question Answering (Misleading ChartQA) Benchmark, a large-scale multimodal dataset designed to assess MLLMs in identifying and reasoning about misleading charts. It contains over 3,000 curated examples, covering 21 types of misleaders and 10 chart types. Each example includes standardized chart code, CSV data, and multiple-choice questions with labeled explanations, validated through multi-round MLLM checks and exhausted expert human review. We benchmark 16 state-of-the-art MLLMs on our dataset, revealing their limitations in identifying visually deceptive practices. We also propose a novel pipeline that detects and localizes misleaders, enhancing MLLMs' accuracy in misleading chart interpretation. Our work establishes a foundation for advancing MLLM-driven misleading chart comprehension. We publicly release the sample dataset to support further research in this critical area.

[Arxiv](https://arxiv.org/abs/2503.18172)