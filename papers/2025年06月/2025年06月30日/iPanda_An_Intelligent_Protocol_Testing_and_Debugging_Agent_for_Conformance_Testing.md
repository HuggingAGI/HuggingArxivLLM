# iPanda: 专为一致性测试设计的智能协议测试与调试代理

发布时间：2025年06月30日

`LLM应用` `软件工程` `测试自动化`

> iPanda: An Intelligent Protocol Testing and Debugging Agent for Conformance Testing

# 摘要

> 协议符合性测试是确保协议实现与规范一致的关键所在。然而，传统方法需要手动创建大量测试用例和脚本，导致过程繁琐且效率低下。近年来，大型语言模型（LLMs）在文本理解和代码生成方面表现出了惊人能力，为自动化测试带来了新机遇。本文中，我们提出了iPanda，这是首个利用LLMs实现协议符合性测试自动化的端到端框架。给定协议规范文档及其实现，iPanda首先采用基于关键词的方法自动生成全面测试用例，然后利用基于代码的检索增强生成方法有效解析实现并生成可执行测试代码。为了进一步提升代码质量，iPanda引入了迭代自校正机制以交互方式优化生成的测试脚本。最后，通过执行和分析生成的测试，iPanda系统性地验证了实现与协议规范的一致性。在多种协议上的综合实验表明，iPanda显著优于纯LLM方法，将测试代码生成的成功率（Pass@1）提升了4.675倍到10.751倍。

> Conformance testing is essential for ensuring that protocol implementations comply with their specifications. However, traditional testing approaches involve manually creating numerous test cases and scripts, making the process labor-intensive and inefficient. Recently, Large Language Models (LLMs) have demonstrated impressive text comprehension and code generation abilities, providing promising opportunities for automation. In this paper, we propose iPanda, the first end-to-end framework that leverages LLMs to automate protocol conformance testing. Given a protocol specification document and its implementation, iPanda first employs a keyword-based method to automatically generate comprehensive test cases. Then, it utilizes a code-based retrieval-augmented generation approach to effectively interpret the implementation and produce executable test code. To further enhance code quality, iPanda incorporates an iterative self-correction mechanism to refine generated test scripts interactively. Finally, by executing and analyzing the generated tests, iPanda systematically verifies compliance between implementations and protocol specifications. Comprehensive experiments on various protocols show that iPanda significantly outperforms pure LLM-based approaches, improving the success rate (Pass@1) of test-code generation by factors ranging from 4.675 times to 10.751 times.

[Arxiv](https://arxiv.org/abs/2507.00378)