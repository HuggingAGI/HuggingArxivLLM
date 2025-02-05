# LLM 助力 Java 验证的下一步

发布时间：2025年02月03日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成代码规范，并进一步利用演绎验证工具集来验证这些规范的正确性。这属于LLM在实际应用中的使用，特别是与软件工程和代码生成相关的应用场景。因此，将其分类为“LLM应用”是合适的。` `软件工程` `编程语言`

> Next Steps in LLM-Supported Java Verification

# 摘要

> 最新研究表明，大型语言模型（LLMs）不仅能生成代码，还能生成基于注释的代码规范。扩展这些方法有望为大规模软件系统提供可证明的正确性保证。相比其他LLM任务，演绎验证领域的显著优势在于其提供了一套严格的工具集，用于验证LLM生成的解决方案。本文初步探讨了如何利用这套工具集，从不可靠的LLM中可靠地提取正确的规范注释。

> Recent work has shown that Large Language Models (LLMs) are not only a suitable tool for code generation but also capable of generating annotation-based code specifications. Scaling these methodologies may allow us to deduce provable correctness guarantees for large-scale software systems. In comparison to other LLM tasks, the application field of deductive verification has the notable advantage of providing a rigorous toolset to check LLM-generated solutions. This short paper provides early results on how this rigorous toolset can be used to reliably elicit correct specification annotations from an unreliable LLM oracle.

[Arxiv](https://arxiv.org/abs/2502.01573)