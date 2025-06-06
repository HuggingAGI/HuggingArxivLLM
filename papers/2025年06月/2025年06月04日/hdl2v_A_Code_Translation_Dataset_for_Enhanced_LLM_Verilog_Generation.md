# hdl2v：助力 LLM 提升 Verilog 代码生成能力的代码翻译数据集

发布时间：2025年06月04日

`LLM应用` `电子工程`

> hdl2v: A Code Translation Dataset for Enhanced LLM Verilog Generation

# 摘要

> 大型语言模型（LLMs）在代码生成领域，尤其是硬件代码生成中，正发挥着越来越重要的作用，其中Verilog是关键语言。然而，公开可用的Verilog代码数量远不及Python等软件语言。本研究提出了一种名为hdl2v（“HDL-to-Verilog”）的数据集，通过将VHDL、Chisel和PyMTL3三种硬件描述语言翻译或编译为Verilog，以增加可用的人类编写Verilog数据的数量。我们进一步展示了hdl2v在提升LLM的Verilog生成能力方面的价值：在VerilogEvalV2上，一个320亿参数的开源权重模型的性能提升了高达23%（pass@10），且未采用任何数据增强或来自更大模型的知识蒸馏。此外，hdl2v在基于数据增强的微调方法上实现了63%的性能提升。最后，我们对数据集进行了特征分析，以更好地理解未来工作中哪些HDL-to-Verilog数据集的特性可以进一步扩展，从而实现更好的性能。

> Large language models (LLMs) are playing an increasingly large role in domains such as code generation, including hardware code generation, where Verilog is the key language. However, the amount of publicly available Verilog code pales in comparison to the amount of code available for software languages like Python. In this work, we present hdl2v ("HDL-to-Verilog"), a dataset which seeks to increase the amount of available human-written Verilog data by translating or compiling three other hardware description languages - VHDL, Chisel, and PyMTL3 - to Verilog. Furthermore, we demonstrate the value of hdl2v in enhancing LLM Verilog generation by improving performance of a 32 billion-parameter open-weight model by up to 23% (pass@10) in VerilogEvalV2, without utilizing any data augmentation or knowledge distillation from larger models. We also show hdl2v's ability to boost the performance of a data augmentation-based fine-tuning approach by 63%. Finally, we characterize and analyze our dataset to better understand which characteristics of HDL-to-Verilog datasets can be expanded upon in future work for even better performance.

[Arxiv](https://arxiv.org/abs/2506.04544)