# LASA：借助 LLM 辅助属性生成优化片上系统安全验证

发布时间：2025年06月21日

`LLM应用` `电子设计自动化` `芯片设计`

> LASA: Enhancing SoC Security Verification with LLM-Aided Property Generation

# 摘要

> 现代片上系统（SoC）设计的安全性保障面临严峻挑战，主要源于设计复杂性和知识产权（IP）模块中分散的资产。形式属性验证（FPV）虽能通过安全属性和模型检查器对设计行为进行建模与验证，但现有方法依赖大量手动操作，导致效率低下、成本高昂且错误频发。大型语言模型（LLMs）在硬件描述语言（HDL）代码生成和验证任务中展现出卓越能力，然而现有基于LLM的技术仍存在生成空洞断言、缺乏高效提示生成、全面验证及错误检测等问题。

本文提出LASA框架，创新性地结合LLMs与检索增强生成（RAG）技术，从基于总线的SoC设计规范和相关文档中自动生成非空洞的安全属性和SystemVerilog断言（SVA）。LASA集成商业电子设计自动化（EDA）工具进行形式属性验证，生成覆盖率指标，并通过反馈循环迭代优化提示，持续提升验证覆盖率。实验结果表明，LASA在多种开源SoC设计中实现了平均88%的高覆盖率，充分验证了其通过高效生成安全属性和SVA实现全面验证的能力。此外，LASA在Hack@DAC'24竞赛中成功识别出有缺陷的OpenTitan SoC中的五个独特错误，进一步彰显了其强大的错误检测能力。

> Ensuring the security of modern System-on-Chip (SoC) designs poses significant challenges due to increasing complexity and distributed assets across the intellectual property (IP) blocks. Formal property verification (FPV) provides the capability to model and validate design behaviors through security properties with model checkers; however, current practices require significant manual efforts to create such properties, making them time-consuming, costly, and error-prone. The emergence of Large Language Models (LLMs) has showcased remarkable proficiency across diverse domains, including HDL code generation and verification tasks. Current LLM-based techniques often produce vacuous assertions and lack efficient prompt generation, comprehensive verification, and bug detection. This paper presents LASA, a novel framework that leverages LLMs and retrieval-augmented generation (RAG) to produce non-vacuous security properties and SystemVerilog Assertions (SVA) from design specifications and related documentation for bus-based SoC designs. LASA integrates commercial EDA tool for FPV to generate coverage metrics and iteratively refines prompts through a feedback loop to enhance coverage. The effectiveness of LASA is validated through various open-source SoC designs, demonstrating high coverage values with an average of ~88\%, denoting comprehensive verification through efficient generation of security properties and SVAs. LASA also demonstrates bug detection capabilities, identifying five unique bugs in the buggy OpenTitan SoC from Hack@DAC'24 competition.

[Arxiv](https://arxiv.org/abs/2506.17865)