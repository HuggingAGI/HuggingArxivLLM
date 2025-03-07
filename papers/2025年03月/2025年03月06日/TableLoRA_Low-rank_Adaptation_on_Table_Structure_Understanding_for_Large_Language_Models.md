# TableLoRA：面向大型语言模型的表格结构理解低秩适配方法

发布时间：2025年03月06日

`LLM应用` `数据处理`

> TableLoRA: Low-rank Adaptation on Table Structure Understanding for Large Language Models

# 摘要

> 表格数据在众多领域中扮演着关键角色，而大型语言模型（LLMs）在高参数效率范式下对表格数据的理解尤为重要。然而，将参数高效微调（PEFT）技术直接应用于表格任务面临诸多挑战，尤其是在实现更好的表格序列化以及在一维序列中表示二维结构化信息方面。为了解决这一问题，我们提出了TableLoRA，一个专为提升LLMs在PEFT过程中对表格结构理解能力而设计的模块。它通过特殊标记对表格进行序列化，并采用2D LoRA对单元格位置的低秩信息进行编码。在四个与表格相关的数据集上的实验结果表明，TableLoRA不仅优于普通的LoRA，还在控制实验中超越了多种表格编码方法。这些发现表明，作为特定于表格的LoRA，TableLoRA显著增强了LLMs处理表格数据的能力，尤其在低参数设置下表现突出，展现出其作为处理表格相关任务的稳健解决方案的潜力。

> Tabular data are crucial in many fields and their understanding by large language models (LLMs) under high parameter efficiency paradigm is important. However, directly applying parameter-efficient fine-tuning (PEFT) techniques to tabular tasks presents significant challenges, particularly in terms of better table serialization and the representation of two-dimensional structured information within a one-dimensional sequence. To address this, we propose TableLoRA, a module designed to improve LLMs' understanding of table structure during PEFT. It incorporates special tokens for serializing tables with special token encoder and uses 2D LoRA to encode low-rank information on cell positions. Experiments on four tabular-related datasets demonstrate that TableLoRA consistently outperforms vanilla LoRA and surpasses various table encoding methods tested in control experiments. These findings reveal that TableLoRA, as a table-specific LoRA, enhances the ability of LLMs to process tabular data effectively, especially in low-parameter settings, demonstrating its potential as a robust solution for handling table-related tasks.

[Arxiv](https://arxiv.org/abs/2503.04396)