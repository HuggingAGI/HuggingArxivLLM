# 基于大型语言模型的Spec2Assertion：自动预RTL断言生成，采用渐进式正则化技术

发布时间：2025年05月12日

`LLM应用

理由：该论文探讨了如何利用大型语言模型（LLMs）自动生成SystemVerilog断言，这是一个具体的任务应用，属于LLM的应用领域。文中提到的方法和评估体系都是围绕如何有效应用LLMs来提升断言生成的效率和质量，因此归类为LLM应用。` `数字芯片设计` `电子设计自动化`

> Spec2Assertion: Automatic Pre-RTL Assertion Generation using Large Language Models with Progressive Regularization

# 摘要

> SystemVerilog断言（SVAs）在数字芯片设计中对检测和修复功能性缺陷至关重要。然而，传统上生成SVAs的过程耗时费力且容易出错。近年来，尤其是借助机器学习和大型语言模型（LLMs）的自动断言生成技术取得了显著进展，尽管大部分方法仍处于初级阶段。我们提出了一种名为Spec2Assertion的新方法，能够在RTL实现前从设计规范中自动生成断言。该技术通过渐进式正则化优化大语言模型，并结合链式思维（CoT）提示来指导断言生成。同时，我们设计了一种全新的评估体系，能够全面衡量断言质量在各种场景下的表现。实验结果表明，在多个基准设计上，Spec2Assertion生成的语法正确断言数量比现有最优方法高出70%，并且平均质量提升了一倍。

> SystemVerilog Assertions (SVAs) play a critical role in detecting and debugging functional bugs in digital chip design. However, generating SVAs has traditionally been a manual, labor-intensive, and error-prone process. Recent advances in automatic assertion generation, particularly those using machine learning and large language models (LLMs), have shown promising potential, though most approaches remain in the early stages of development. In this work, we introduce Spec2Assertion, a new technique for automatically generating assertions from design specifications prior to RTL implementation. It leverages LLMs with progressive regularization and incorporates Chain-of-Thought (CoT) prompting to guide assertion synthesis. Additionally, we propose a new evaluation methodology that assesses assertion quality across a broad range of scenarios. Experiments on multiple benchmark designs show that Spec2Assertion generates 70% more syntax-correct assertions with 2X quality improvement on average compared to a recent state-of-the-art approach.

[Arxiv](https://arxiv.org/abs/2505.07995)