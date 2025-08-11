# LLM 生成 RTL 代码的错误：理解和缓解

发布时间：2025年08月07日

`LLM应用

摘要讨论了如何改进大型语言模型在生成RTL代码中的应用，通过结合检索增强生成（RAG）等技术，显著提升了准确率。因此，这篇论文属于LLM应用类别。` `电子设计自动化` `代码生成`

> Understanding and Mitigating Errors of LLM-Generated RTL Code

# 摘要

> 尽管基于大型语言模型（LLM）的寄存器传输级（RTL）代码生成展现了巨大潜力，但整体成功率仍有待提升。错误源于多种因素，而对具体失败原因的有限理解限制了改进空间。为此，我们进行了全面的错误分析和分类。研究发现，大多数错误并非源于LLM推理能力的局限，而是由于RTL编程知识不足、电路概念理解不深、设计描述模糊，或对复杂多模态输入的误解。基于上下文学习，我们提出了针对性的错误修正技术。具体而言，我们构建了领域特定的知识库，并采用检索增强生成（RAG）提供必要的RTL知识。为缓解模糊性错误，我们制定了设计描述规则并实施了规则检查机制。针对多模态误解，我们集成了外部工具将输入转换为LLM兼容的元格式。对于剩余错误，我们采用迭代调试循环（仿真-错误定位-修正）。将这些技术整合到基于LLM的框架中，显著提升了性能。实验结果表明，我们的增强框架在VerilogEval基准测试中达到了91.0%的准确率，比基线代码生成方法高出32.7%，充分证明了我们方法的有效性。

> Despite the promising potential of large language model (LLM) based register-transfer-level (RTL) code generation, the overall success rate remains unsatisfactory. Errors arise from various factors, with limited understanding of specific failure causes hindering improvement. To address this, we conduct a comprehensive error analysis and manual categorization. Our findings reveal that most errors stem not from LLM reasoning limitations, but from insufficient RTL programming knowledge, poor understanding of circuit concepts, ambiguous design descriptions, or misinterpretation of complex multimodal inputs. Leveraging in-context learning, we propose targeted error correction techniques. Specifically, we construct a domain-specific knowledge base and employ retrieval-augmented generation (RAG) to supply necessary RTL knowledge. To mitigate ambiguity errors, we introduce design description rules and implement a rule-checking mechanism. For multimodal misinterpretation, we integrate external tools to convert inputs into LLM-compatible meta-formats. For remaining errors, we adopt an iterative debugging loop (simulation-error localization-correction). Integrating these techniques into an LLM-based framework significantly improves performance. We incorporate these error correction techniques into a foundational LLM-based RTL code generation framework, resulting in significantly improved performance. Experimental results show that our enhanced framework achieves 91.0\% accuracy on the VerilogEval benchmark, surpassing the baseline code generation approach by 32.7\%, demonstrating the effectiveness of our methods.

[Arxiv](https://arxiv.org/abs/2508.05266)