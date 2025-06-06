# # MELABenchv1：针对低资源马耳他语NLP任务，评估大型语言模型与小样本微调模型的基准测试工具

发布时间：2025年06月04日

`LLM应用` `语言技术`

> MELABenchv1: Benchmarking Large Language Models against Smaller Fine-Tuned Models for Low-Resource Maltese NLP

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理（NLP）任务中表现卓越，这得益于其强大的泛化能力和无需额外训练即可执行任务的特性。然而，这些模型在资源较少语言上的效果仍有待提升。本研究通过一个涵盖11项判别与生成任务的新基准，评估了55个公开可用的LLMs在马耳他语（一种资源较少语言）上的性能。实验结果表明，多数模型表现欠佳，尤其在生成任务中，而经过微调的小型模型在所有任务上往往表现更优。通过多维度分析，我们深入探讨了影响模型性能的各项因素。研究发现，模型在预训练及指令调整阶段对马耳他语的先前接触是决定性能的关键因素。此外，我们还分析了微调与提示方法的权衡，指出尽管微调需要更高的初始投入，但它能带来更佳的性能表现和更低的推理成本。本研究旨在强调开发更具包容性的语言技术的重要性，并建议从事资源较少语言研究的研究者考虑更多“传统”的语言建模方法。

> Large Language Models (LLMs) have demonstrated remarkable performance across various Natural Language Processing (NLP) tasks, largely due to their generalisability and ability to perform tasks without additional training. However, their effectiveness for low-resource languages remains limited. In this study, we evaluate the performance of 55 publicly available LLMs on Maltese, a low-resource language, using a newly introduced benchmark covering 11 discriminative and generative tasks. Our experiments highlight that many models perform poorly, particularly on generative tasks, and that smaller fine-tuned models often perform better across all tasks. From our multidimensional analysis, we investigate various factors impacting performance. We conclude that prior exposure to Maltese during pre-training and instruction-tuning emerges as the most important factor. We also examine the trade-offs between fine-tuning and prompting, highlighting that while fine-tuning requires a higher initial cost, it yields better performance and lower inference costs. Through this work, we aim to highlight the need for more inclusive language technologies and recommend that researchers working with low-resource languages consider more "traditional" language modelling approaches.

[Arxiv](https://arxiv.org/abs/2506.04385)