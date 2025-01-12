# 从科学文本到可验证代码：Transformers驱动的自动化过程

发布时间：2025年01月09日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLM）中的transformer技术来自动化形式化验证过程，即将研究论文中的形式化证明转化为可验证的代码。这属于LLM在实际应用中的使用，旨在解决形式化验证的难题，提升代码的可靠性和安全性。因此，将其分类为“LLM应用”是合适的。` `软件工程` `形式化验证`

> From Scientific Texts to Verifiable Code: Automating the Process with Transformers

# 摘要

> 尽管大量研究文献提出了具有形式化保证的算法，但当今系统中可验证的代码仍然寥寥无几。这一差距源于验证代码的固有难度，尤其是形式化验证工具所需的耗时性和严格的证明细节。然而，大型语言模型中transformer的出现为解决这一挑战带来了希望。在这篇立场论文中，我们认为transformer能够阅读提出形式化证明算法的研究论文，并将这些证明转化为可验证的代码。我们利用transformer首先基于论文原文构建证明的形式化结构，然后处理人类常忽略的繁琐、低层次证明细节。这种方法有望显著降低形式化验证的门槛。通过阅读论文生成可验证代码的想法，为自动化复杂系统的验证开辟了新途径，使得学术研究中的形式化验证算法能够更顺畅地应用于现实世界的软件系统，从而提升代码的可靠性和安全性。

> Despite the vast body of research literature proposing algorithms with formal guarantees, the amount of verifiable code in today's systems remains minimal. This discrepancy stems from the inherent difficulty of verifying code, particularly due to the time-consuming nature and strict formalism of proof details that formal verification tools require. However, the emergence of transformers in Large Language Models presents a promising solution to this challenge. In this position paper, we believe that transformers have the potential to read research papers that propose algorithms with formal proofs and translate these proofs into verifiable code. We leverage transformers to first build a formal structure of the proof using the original text from the paper, and then to handle the tedious, low-level aspects of proofs that are often omitted by humans. We argue that this approach can significantly reduce the barrier to formal verification. The above idea of reading papers to write verifiable code opens new avenues for automating the verification of complex systems, enabling a future where formally verified algorithms from academic research can more seamlessly transition into real-world software systems, thereby improving code reliability and security.

[Arxiv](https://arxiv.org/abs/2501.05252)