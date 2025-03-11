# # TPU-Gen：定制张量处理单元的LLM驱动生成器

发布时间：2025年03月07日

`LLM应用` `硬件加速器` `硬件设计自动化`

> TPU-Gen: LLM-Driven Custom Tensor Processing Unit Generator

# 摘要

> 深度神经网络 (DNNs) 的复杂性和规模不断提升，推动了对专用张量加速器（如张量处理单元 (TPUs)）的需求，以满足多样化的计算和能效要求。然而，设计最优 TPU 仍面临诸多挑战，包括对领域专业知识的高要求、设计时间的大量投入以及缺乏高质量的领域特定数据集。本文介绍了 TPU-Gen，首个基于大型语言模型 (LLM) 的框架，专注于点积阵列架构，旨在自动化精确和近似 TPU 的生成过程。TPU-Gen 依托一个精心策划、全面且开源的数据集，涵盖了广泛的空域阵列设计和近似乘法累加单元，支持针对不同 DNN 工作负载的设计重用、适应和定制。该框架采用检索增强生成 (RAG) 作为在数据稀缺的硬件领域构建 LLM 的有效解决方案，解决了最引人注目的问题——幻觉现象。通过有效的硬件生成管道，TPU-Gen 将高层次的架构规范转化为优化后的低层次实现。我们的实验评估表明，TPU-Gen 在性能、功耗和面积效率方面表现出色，与手动优化的参考值相比，面积和功耗平均降低了 92% 和 96%。这些成果为推动下一代基于 LLM 的设计自动化工具的发展树立了新标杆。

> The increasing complexity and scale of Deep Neural Networks (DNNs) necessitate specialized tensor accelerators, such as Tensor Processing Units (TPUs), to meet various computational and energy efficiency requirements. Nevertheless, designing optimal TPU remains challenging due to the high domain expertise level, considerable manual design time, and lack of high-quality, domain-specific datasets. This paper introduces TPU-Gen, the first Large Language Model (LLM) based framework designed to automate the exact and approximate TPU generation process, focusing on systolic array architectures. TPU-Gen is supported with a meticulously curated, comprehensive, and open-source dataset that covers a wide range of spatial array designs and approximate multiply-and-accumulate units, enabling design reuse, adaptation, and customization for different DNN workloads. The proposed framework leverages Retrieval-Augmented Generation (RAG) as an effective solution for a data-scare hardware domain in building LLMs, addressing the most intriguing issue, hallucinations. TPU-Gen transforms high-level architectural specifications into optimized low-level implementations through an effective hardware generation pipeline. Our extensive experimental evaluations demonstrate superior performance, power, and area efficiency, with an average reduction in area and power of 92\% and 96\% from the manual optimization reference values. These results set new standards for driving advancements in next-generation design automation tools powered by LLMs.

[Arxiv](https://arxiv.org/abs/2503.05951)