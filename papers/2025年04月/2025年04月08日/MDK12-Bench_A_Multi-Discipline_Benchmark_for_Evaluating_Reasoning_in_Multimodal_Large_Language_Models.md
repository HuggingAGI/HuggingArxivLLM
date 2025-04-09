# MDK12-Bench：一个多学科基准测试，专为评估多模态大型语言模型的推理能力而设计。

发布时间：2025年04月08日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）的推理能力评估，并提出了一种新的基准测试和动态评估框架。它属于将大型语言模型应用于具体任务（如推理和跨学科评估）的范畴，因此归类为LLM应用。` `多模态推理` `跨学科评估`

> MDK12-Bench: A Multi-Discipline Benchmark for Evaluating Reasoning in Multimodal Large Language Models

# 摘要

> 多模态推理是人类智能的基本方面，它将语言和视觉线索整合到问题解决和决策中，是通向人工通用智能的关键一步。然而，目前评估多模态大型语言模型（MLLMs）的推理能力仍存在不足。现有的推理基准测试大多受限于数据量有限、领域覆盖狭窄以及知识分布零散。为了解决这些问题，我们推出了MDK12-Bench，这是一个跨学科的基准测试，通过K-12阶段的考试来全面评估MLLMs的推理能力。MDK12-Bench涵盖了数学、物理、化学、生物、地理和信息科学六个学科，包含从小学到高中12年级不同难度级别的14万多个推理实例。该基准测试基于有组织的知识结构，提供了6,827个实例级知识点标注、详细的答案解释、难度标签和跨年份划分，为全面评估提供了强大支持。此外，我们还提出了一种新型动态评估框架，通过在评估过程中引导问题形式、问题类型和图像风格，有效缓解数据污染问题。在MDK12-Bench上进行的广泛实验揭示了当前MLLMs在多模态推理方面的重大局限性。我们的研究发现为下一代模型的发展提供了重要启示。数据和代码可在GitHub上获取：https://github.com/LanceZPF/MDK12。

> Multimodal reasoning, which integrates language and visual cues into problem solving and decision making, is a fundamental aspect of human intelligence and a crucial step toward artificial general intelligence. However, the evaluation of multimodal reasoning capabilities in Multimodal Large Language Models (MLLMs) remains inadequate. Most existing reasoning benchmarks are constrained by limited data size, narrow domain coverage, and unstructured knowledge distribution. To close these gaps, we introduce MDK12-Bench, a multi-disciplinary benchmark assessing the reasoning capabilities of MLLMs via real-world K-12 examinations. Spanning six disciplines (math, physics, chemistry, biology, geography, and information science), our benchmark comprises 140K reasoning instances across diverse difficulty levels from primary school to 12th grade. It features 6,827 instance-level knowledge point annotations based on a well-organized knowledge structure, detailed answer explanations, difficulty labels and cross-year partitions, providing a robust platform for comprehensive evaluation. Additionally, we present a novel dynamic evaluation framework to mitigate data contamination issues by bootstrapping question forms, question types, and image styles during evaluation. Extensive experiment on MDK12-Bench reveals the significant limitation of current MLLMs in multimodal reasoning. The findings on our benchmark provide insights into the development of the next-generation models. Our data and codes are available at https://github.com/LanceZPF/MDK12.

[Arxiv](https://arxiv.org/abs/2504.05782)