# 全面Verilog设计问题：下一代评估大型语言模型与智能体RTL设计与验证能力的基准数据集

发布时间：2025年06月16日

`LLM应用` `硬件设计与验证` `硬件设计自动化`

> Comprehensive Verilog Design Problems: A Next-Generation Benchmark Dataset for Evaluating Large Language Models and Agents on RTL Design and Verification

# 摘要

> 我们正式推出 Comprehensive Verilog Design Problems (CVDP) 基准测试，这是一个全新的数据集和基础设施，旨在推动大型语言模型（LLM）及智能体在硬件设计与验证领域的研究进展。CVDP 包含 13 个任务类别的 783 个问题，涵盖 RTL 生成、验证、调试、规格对齐以及技术问答，所有问题均由经验丰富的硬件工程师编写。这些问题以非智能体和智能体两种格式提供。与先前的工作相比，CVDP 引入了更加现实且具有挑战性的背景，即使是最先进的模型在代码生成方面也只能达到 34% 的 pass@1 率。智能体任务——尤其是涉及 RTL 复用和验证的任务——尤其具有难度。评估采用开源工具和模型评分基础设施，理解任务则通过 BLEU 和基于 LLM 的评分进行评估。CVDP 揭示了当前模型能力的巨大差距，凸显了在实现稳健、现实世界的硬件设计自动化方面，持续研究的必要性。

> We present the Comprehensive Verilog Design Problems (CVDP) benchmark, a new dataset and infrastructure to advance LLM and agent research in hardware design and verification. CVDP includes 783 problems across 13 task categories, covering RTL generation, verification, debugging, specification alignment, and technical Q&A authored by experienced hardware engineers. Problems are offered in both non-agentic and agentic formats. The benchmark introduces more realistic and challenging contexts than prior work, with state-of-the-art models achieving no more than 34% pass@1 on code generation. Agentic tasks$\unicode{x2013}$especially those involving RTL reuse and verification$\unicode{x2013}$are particularly difficult. Evaluation uses open-source tools and model scoring infrastructure, with comprehension tasks assessed via BLEU and LLM-based judging. CVDP reveals substantial gaps in current model capabilities, underscoring the need for continued research toward robust, real-world hardware design automation.

[Arxiv](https://arxiv.org/abs/2506.14074)