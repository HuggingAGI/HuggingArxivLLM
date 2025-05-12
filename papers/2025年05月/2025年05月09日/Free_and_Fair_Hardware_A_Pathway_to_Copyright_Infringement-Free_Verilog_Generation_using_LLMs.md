# # 自由公平的硬件：探索利用大语言模型实现无版权侵犯的Verilog生成之路

发布时间：2025年05月09日

`LLM应用` `硬件设计` `EDA`

> Free and Fair Hardware: A Pathway to Copyright Infringement-Free Verilog Generation using LLMs

# 摘要

> 大型语言模型（LLM）在硬件设计任务中的能力局限，尤其是生成功能性Verilog代码方面，推动了基于开源硬件数据集的微调优化尝试。然而，现有数据集规模有限且缺乏有效的版权复用检查，可能导致微调后的LLM产生版权纠纷。为此，我们提出了一个评估基准，用于量化Verilog训练LLM生成受版权保护代码的风险。为降低这一风险，我们开源了包含超22万份文件的Verilog数据集FreeSet，并提供了确保公平使用Verilog数据的自动化数据整理框架。通过持续预训练的微调框架，我们开发了专为Verilog优化的FreeV模型。实验结果显示，FreeV在前作中版权侵权风险最低，仅3%的违规率。同时，FreeV在Verilog生成能力上显著超越其基础模型，VerilogEval的pass@10通过率提升超10%。

> Limitations in Large Language Model (LLM) capabilities for hardware design tasks, such as generating functional Verilog codes, have motivated various fine-tuning optimizations utilizing curated hardware datasets from open-source repositories. However, these datasets remain limited in size and contain minimal checks on licensing for reuse, resulting in potential copyright violations by fine-tuned LLMs. Therefore, we propose an evaluation benchmark to estimate the risk of Verilog-trained LLMs to generate copyright-protected codes. To minimize this risk, we present an open-source Verilog dataset, FreeSet, containing over 220k files, along with the automated dataset curation framework utilized to provide additional guarantees of fair-use Verilog data. We then execute an LLM fine-tuning framework consisting of continual pre-training, resulting in a fine-tuned Llama model for Verilog, FreeV. Our results indicate that FreeV demonstrates the smallest risk of copyright-infringement among prior works, with only a 3% violation rate. Furthermore, experimental results demonstrate improvements in Verilog generation functionality over its baseline model, improving VerilogEval pass@10 rates by over 10%.

[Arxiv](https://arxiv.org/abs/2505.06096)