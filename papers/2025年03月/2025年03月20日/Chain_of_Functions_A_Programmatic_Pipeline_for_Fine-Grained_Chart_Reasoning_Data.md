# 函数链：为精细图表推理数据打造的程序化流水线

发布时间：2025年03月20日

`LLM应用

理由：这篇论文主要探讨了如何利用多模态大型语言模型（MLLMs）处理复杂图表查询，并提出了一种新的数据生成方法Chain of Functions (CoF)。该方法通过生成多样化的推理路径，确保数据的精准与多样性，从而提升模型的性能。虽然涉及LLM的应用，但核心贡献在于数据生成的方法和工具，属于LLM的应用层面。` `视觉推理` `多模态模型`

> Chain of Functions: A Programmatic Pipeline for Fine-Grained Chart Reasoning Data

# 摘要

> 视觉推理是多模态大型语言模型（MLLMs）处理复杂图表查询的关键，但高质量的推理数据仍十分匮乏。现有方法借助（M）LLMs生成数据，但直接提示往往导致精度和多样性不足。本文提出了一种名为\textit{Chain of Functions (CoF)}的新颖程序化推理数据生成管道，通过自由探索推理路径作为监督，确保数据的精准与多样性。具体而言，\textit{CoF}从原子函数（如最大值计算和算术运算）的无监督探索开始，生成多样化的函数链，并仅需一个中等规模的开源LLM将其转化为语言推理和问题。\textit{CoF}的优势显著：1）精准：函数控制的生成减少了幻觉现象；2）多样：函数链的枚举实现了多样的问题分类；3）可解释：函数链作为内置推理，支持细粒度评估；4）实用：摆脱了对极大模型的依赖。借助\textit{CoF}，我们构建了\textit{ChartCoF}数据集，包含1.4k用于细粒度分析的复杂推理问答和50k用于推理增强的问答。在\textit{ChartCoF}上的评估显示，各MLLM在不同问题分类中的性能存在差异，实验表明，使用\textit{ChartCoF}微调的模型在常见基准测试中达到了同规模模型的最先进水平。此外，\textit{CoF}中基于函数的推理生成范式为图表以外的广泛应用开辟了新思路。

> Visual reasoning is crucial for multimodal large language models (MLLMs) to address complex chart queries, yet high-quality rationale data remains scarce. Existing methods leveraged (M)LLMs for data generation, but direct prompting often yields limited precision and diversity. In this paper, we propose \textit{Chain of Functions (CoF)}, a novel programmatic reasoning data generation pipeline that utilizes freely-explored reasoning paths as supervision to ensure data precision and diversity. Specifically, it starts with human-free exploration among the atomic functions (e.g., maximum data and arithmetic operations) to generate diverse function chains, which are then translated into linguistic rationales and questions with only a moderate open-sourced LLM. \textit{CoF} provides multiple benefits: 1) Precision: function-governed generation reduces hallucinations compared to freeform generation; 2) Diversity: enumerating function chains enables varied question taxonomies; 3) Explainability: function chains serve as built-in rationales, allowing fine-grained evaluation beyond overall accuracy; 4) Practicality: eliminating reliance on extremely large models. Employing \textit{CoF}, we construct the \textit{ChartCoF} dataset, with 1.4k complex reasoning Q\&A for fine-grained analysis and 50k Q\&A for reasoning enhancement. The fine-grained evaluation on \textit{ChartCoF} reveals varying performance across question taxonomies for each MLLM, and the experiments also show that finetuning with \textit{ChartCoF} achieves state-of-the-art performance among same-scale MLLMs on widely used benchmarks. Furthermore, the novel paradigm of function-governed rationale generation in \textit{CoF} could inspire broader applications beyond charts.

[Arxiv](https://arxiv.org/abs/2503.16260)