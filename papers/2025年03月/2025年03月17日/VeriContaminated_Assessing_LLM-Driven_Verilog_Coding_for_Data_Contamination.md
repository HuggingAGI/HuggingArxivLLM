# VeriContaminated：评估LLM驱动的Verilog编程中的数据污染

发布时间：2025年03月17日

`LLM应用` `软件工程` `硬件设计`

> VeriContaminated: Assessing LLM-Driven Verilog Coding for Data Contamination

# 摘要

> 大型语言模型（LLMs）在代码生成领域掀起了一场革命，其在各类基准框架上取得了卓越成果。然而，关于数据污染的担忧——即 benchmark 数据无意中泄露到预训练或微调数据集——引发了对这些评估有效性的质疑。尽管这一问题已为人知，并限制了 LLM 驱动的软件工程在工业界的应用，但硬件编码方面却鲜少有人关注这些风险。我们首次分析了 Verilog 代码生成的 state-of-the-art 评估框架（VerilogEval 和 RTLLM），采用了 established methods for contamination detection（CCD 和 Min-K% Prob）。我们考察了 SOTA 商业和开源 LLM（CodeGen2.5、Minitron 4b、Mistral 7b、phi-4 mini、LLaMA-{1,2,3.1}、GPT-{2,3.5,4o}、Deepseek-Coder 和 CodeQwen 1.5），包括 baseline 和微调模型（RTLCoder 和 Verigen）。研究证实数据污染是一个关键问题。我们探讨了缓解措施及其对代码质量与公平性（即减少污染以实现无偏评估）的权衡。

> Large Language Models (LLMs) have revolutionized code generation, achieving exceptional results on various established benchmarking frameworks. However, concerns about data contamination - where benchmark data inadvertently leaks into pre-training or fine-tuning datasets - raise questions about the validity of these evaluations. While this issue is known, limiting the industrial adoption of LLM-driven software engineering, hardware coding has received little to no attention regarding these risks. For the first time, we analyze state-of-the-art (SOTA) evaluation frameworks for Verilog code generation (VerilogEval and RTLLM), using established methods for contamination detection (CCD and Min-K% Prob). We cover SOTA commercial and open-source LLMs (CodeGen2.5, Minitron 4b, Mistral 7b, phi-4 mini, LLaMA-{1,2,3.1}, GPT-{2,3.5,4o}, Deepseek-Coder, and CodeQwen 1.5), in baseline and fine-tuned models (RTLCoder and Verigen). Our study confirms that data contamination is a critical concern. We explore mitigations and the resulting trade-offs for code quality vs fairness (i.e., reducing contamination toward unbiased benchmarking).

[Arxiv](https://arxiv.org/abs/2503.13572)