# MedErr-CT：一个专注于识别与纠正CT报告错误的视觉问答基准测试集

发布时间：2025年06月23日

`LLM应用` `医学图像处理`

> MedErr-CT: A Visual Question Answering Benchmark for Identifying and Correcting Errors in CT Reports

# 摘要

> # 摘要
计算机断层扫描（CT）在临床诊断中发挥着关键作用，但CT检查需求的激增也带来了诊断错误的风险。尽管多模态大型语言模型（MLLMs）在医学知识理解方面展现出巨大潜力，但它们生成不准确信息的倾向凸显了严格验证的必要性。然而，现有的医学视觉问答（VQA）基准主要集中在简单的视觉识别任务上，缺乏临床相关性，无法评估专家级知识。

我们推出MedErr-CT，这是一个通过VQA框架评估医学MLLMs识别和纠正CT报告中错误能力的新基准。该基准涵盖六个错误类别——四个以视觉为中心的错误（遗漏、插入、方向、大小）和两种词汇错误类型（单位、拼写）——并分为三个任务级别：分类、检测和纠正。通过这一基准，我们对最先进的3D医学MLLMs进行了定量评估，揭示了它们在不同错误类型上的能力存在显著差异。

我们的基准为开发更可靠、更具临床应用价值的MLLMs做出了贡献，最终有助于减少诊断错误并提高临床实践中的准确性。代码和数据集可在https://github.com/babbu3682/MedErr-CT获取。

> Computed Tomography (CT) plays a crucial role in clinical diagnosis, but the growing demand for CT examinations has raised concerns about diagnostic errors. While Multimodal Large Language Models (MLLMs) demonstrate promising comprehension of medical knowledge, their tendency to produce inaccurate information highlights the need for rigorous validation. However, existing medical visual question answering (VQA) benchmarks primarily focus on simple visual recognition tasks, lacking clinical relevance and failing to assess expert-level knowledge. We introduce MedErr-CT, a novel benchmark for evaluating medical MLLMs' ability to identify and correct errors in CT reports through a VQA framework. The benchmark includes six error categories - four vision-centric errors (Omission, Insertion, Direction, Size) and two lexical error types (Unit, Typo) - and is organized into three task levels: classification, detection, and correction. Using this benchmark, we quantitatively assess the performance of state-of-the-art 3D medical MLLMs, revealing substantial variation in their capabilities across different error types. Our benchmark contributes to the development of more reliable and clinically applicable MLLMs, ultimately helping reduce diagnostic errors and improve accuracy in clinical practice. The code and datasets are available at https://github.com/babbu3682/MedErr-CT.

[Arxiv](https://arxiv.org/abs/2506.19217)