# HaVen: 幻觉缓解的LLM，专为Verilog代码生成设计，与HDL工程师无缝对接

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）生成Verilog代码以实现硬件设计自动化，并提出了一个名为HaVen的框架来减少生成代码中的幻觉问题。这属于LLM在实际应用中的使用，特别是针对硬件描述语言（HDL）工程的需求。因此，将其分类为“LLM应用”是合适的。` `硬件设计` `自动化`

> HaVen: Hallucination-Mitigated LLM for Verilog Code Generation Aligned with HDL Engineers

# 摘要

> # 摘要
最近，利用大型语言模型（LLMs）生成Verilog代码以实现硬件设计自动化，引发了广泛的研究兴趣。然而，现有研究表明，LLMs的能力与硬件描述语言（HDL）工程的实际需求之间存在显著差距，主要体现在工程师提问方式与生成代码中的幻觉问题。为此，我们提出了HaVen，一个创新的LLM框架，旨在减少幻觉并使Verilog代码生成更贴近HDL工程师的实践。HaVen通过引入全面的分类法和思维链（CoT）机制，将符号模态（如真值表、状态图等）转化为精确的自然语言描述，有效解决了幻觉问题。此外，HaVen采用数据增强策略，生成了符合真实HDL工程实践的高质量指令-代码对。实验表明，HaVen显著提升了Verilog代码生成的准确性，在VerilogEval和RTLLM基准测试中超越了现有的基于LLM的Verilog生成方法。HaVen已开源，访问地址为https://github.com/Intelligent-Computing-Research-Group/HaVen。

> Recently, the use of large language models (LLMs) for Verilog code generation has attracted great research interest to enable hardware design automation. However, previous works have shown a gap between the ability of LLMs and the practical demands of hardware description language (HDL) engineering. This gap includes differences in how engineers phrase questions and hallucinations in the code generated. To address these challenges, we introduce HaVen, a novel LLM framework designed to mitigate hallucinations and align Verilog code generation with the practices of HDL engineers. HaVen tackles hallucination issues by proposing a comprehensive taxonomy and employing a chain-of-thought (CoT) mechanism to translate symbolic modalities (e.g. truth tables, state diagrams, etc.) into accurate natural language descriptions. Furthermore, HaVen bridges this gap by using a data augmentation strategy. It synthesizes high-quality instruction-code pairs that match real HDL engineering practices. Our experiments demonstrate that HaVen significantly improves the correctness of Verilog code generation, outperforming state-of-the-art LLM-based Verilog generation methods on VerilogEval and RTLLM benchmark. HaVen is publicly available at https://github.com/Intelligent-Computing-Research-Group/HaVen.

[Arxiv](https://arxiv.org/abs/2501.04908)