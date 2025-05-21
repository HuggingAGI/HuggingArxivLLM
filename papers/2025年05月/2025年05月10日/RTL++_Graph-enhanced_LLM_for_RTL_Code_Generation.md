# # RTL++: 基于图增强的大型语言模型实现RTL代码生成

发布时间：2025年05月10日

`LLM应用` `EDA` `硬件设计`

> RTL++: Graph-enhanced LLM for RTL Code Generation

# 摘要

> 硬件设计复杂性的提升使得电子设计自动化（EDA）领域迫切需要更高级别的自动化。传统的寄存器传输级（RTL）设计方法不仅耗时，还容易出错。商用大型语言模型（LLMs）虽然在自动化方面展现出巨大潜力，但其安全和隐私问题不容忽视。开源模型虽提供了一种替代方案，但受限于高质量RTL代码数据的缺乏，往往在质量和正确性上表现不足。本文提出了一种全新的基于大型语言模型辅助的RTL代码生成方法——RTL++，它通过利用代码结构的图表示来显著提升生成代码的质量。通过将RTL代码编码为文本化的控制流图（CFG）和数据流图（DFG），RTL++能够深入捕捉代码内部的层次结构、依赖关系和相互关系。这种基于结构化图的方法为大型语言模型提供了更丰富的上下文信息，使其能够更精准地理解和生成指令。通过专注于基于图表示的数据生成，RTL++成功解决了传统方法仅依赖代码而导致的多样性不足问题。实验结果表明，RTL++在VerilogEval基准的Pass@1/5/10指标评估下，优于现有的针对RTL生成的最先进模型，同时也优于RTLLM1.1模型。这一结果凸显了增强上下文在提升基于大型语言模型的RTL代码生成能力方面的显著效果。

> As hardware design complexity escalates, there is an urgent need for advanced automation in electronic design automation (EDA). Traditional register transfer level (RTL) design methods are manual, time-consuming, and prone to errors. While commercial (instruction-tuned) large language models (LLMs) shows promising performance for automation, they pose security and privacy concerns. Open-source models offer alternatives; however, they frequently fall short in quality/correctness, largely due to limited, high-quality RTL code data essential for effective training and generalization. This paper proposes RTL++, a first-of-its-kind LLM-assisted method for RTL code generation that utilizes graph representations of code structures to enhance the quality of generated code. By encoding RTL code into a textualized control flowgraphs (CFG) and data flow graphs (DFG), RTL++ captures the inherent hierarchy, dependencies, and relationships within the code. This structured graph-based approach enhances the context available to LLMs, enabling them to better understand and generate instructions. By focusing on data generation through graph representations, RTL++ addresses the limitations of previous approaches that rely solely on code and suffer from lack of diversity. Experimental results demonstrate that RTL++ outperforms state-of-the-art models fine-tuned for RTL generation, as evaluated using the VerilogEval benchmark's Pass@1/5/10 metric, as well as the RTLLM1.1 model, which highlight the effectiveness of graph-enhanced context in advancing the capabilities of LLM-assisted RTL code generation.

[Arxiv](https://arxiv.org/abs/2505.13479)