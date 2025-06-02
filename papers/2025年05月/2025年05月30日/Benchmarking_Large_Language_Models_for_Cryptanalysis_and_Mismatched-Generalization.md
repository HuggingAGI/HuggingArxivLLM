# 评估大型语言模型在密码分析和不匹配泛化中的基准性能

发布时间：2025年05月30日

`LLM应用

这篇论文探讨了大型语言模型在密码分析中的应用潜力，评估了它们在解密任务中的表现，属于LLM的应用研究。` `密码学`

> Benchmarking Large Language Models for Cryptanalysis and Mismatched-Generalization

# 摘要

> 大型语言模型（LLMs）的最新进展彻底改变了自然语言理解和生成领域，推动了在各类任务上的广泛基准测试工作。然而，作为数据安全和加密关键领域的密码分析，在LLM评估中尚未得到充分探索。为了填补这一研究空白，我们评估了最先进的LLMs在使用多种加密算法生成的加密文本上的密码分析潜力。我们引入了一个新型基准数据集，包含涵盖不同领域、长度、写作风格和主题的多样化明文，并与它们的加密版本配对。通过零样本和少样本设置，我们评估了多个LLMs在不同加密方案下的解密准确性和语义理解能力。研究发现揭示了LLMs在侧信道通信中的优势和局限性，同时引发了对其易受越狱攻击的担忧。这项研究突出了LLMs在安全背景下的双重用途，并为AI安全和安全的讨论做出了贡献。

> Recent advancements in Large Language Models (LLMs) have transformed natural language understanding and generation, leading to extensive benchmarking across diverse tasks. However, cryptanalysis a critical area for data security and encryption has not yet been thoroughly explored in LLM evaluations. To address this gap, we evaluate cryptanalytic potential of state of the art LLMs on encrypted texts generated using a range of cryptographic algorithms. We introduce a novel benchmark dataset comprising diverse plain texts spanning various domains, lengths, writing styles, and topics paired with their encrypted versions. Using zero-shot and few shot settings, we assess multiple LLMs for decryption accuracy and semantic comprehension across different encryption schemes. Our findings reveal key insights into the strengths and limitations of LLMs in side-channel communication while raising concerns about their susceptibility to jailbreaking attacks. This research highlights the dual-use nature of LLMs in security contexts and contributes to the ongoing discussion on AI safety and security.

[Arxiv](https://arxiv.org/abs/2505.24621)