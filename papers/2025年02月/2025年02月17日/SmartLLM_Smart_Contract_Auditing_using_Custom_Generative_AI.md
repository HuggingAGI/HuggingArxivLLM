# SmartLLM：利用定制生成式AI进行智能合约审计

发布时间：2025年02月17日

`LLM应用

论文摘要：智能合约是去中心化金融（DeFi）和区块链生态系统的基石，但随着编码错误和复杂攻击手段的增加，它们正面临日益严峻的安全威胁。传统静态分析工具和现有漏洞检测方法往往难以全面应对这些挑战，导致高误报率和无法检测动态漏洞的困境。本文提出了一种名为SmartLLM的创新方法，该方法基于微调的LLaMA 3.1模型，并结合检索增强生成（RAG）技术，显著提升了智能合约审计的准确性和效率。通过整合ERC标准的领域知识，并采用QLoRA等先进技术进行高效微调，SmartLLM在性能上超越了Mythril和Slither等静态分析工具，以及GPT-3.5和GPT-4等零样本大型语言模型（LLM）提示方法。实验结果展示了100%的完美召回率和70%的准确率，充分证明了该模型在识别漏洞（包括重入攻击和访问控制问题）方面的卓越能力。这项研究通过提供一种可扩展且有效的审计解决方案，推动了智能合约安全的发展，为去中心化应用的安全采用提供了坚实支持。

LLM应用` `区块链`

> SmartLLM: Smart Contract Auditing using Custom Generative AI

# 摘要

> 智能合约是去中心化金融（DeFi）和区块链生态系统的基石，但随着编码错误和复杂攻击手段的增加，它们正面临日益严峻的安全威胁。传统静态分析工具和现有漏洞检测方法往往难以全面应对这些挑战，导致高误报率和无法检测动态漏洞的困境。本文提出了一种名为SmartLLM的创新方法，该方法基于微调的LLaMA 3.1模型，并结合检索增强生成（RAG）技术，显著提升了智能合约审计的准确性和效率。通过整合ERC标准的领域知识，并采用QLoRA等先进技术进行高效微调，SmartLLM在性能上超越了Mythril和Slither等静态分析工具，以及GPT-3.5和GPT-4等零样本大型语言模型（LLM）提示方法。实验结果展示了100%的完美召回率和70%的准确率，充分证明了该模型在识别漏洞（包括重入攻击和访问控制问题）方面的卓越能力。这项研究通过提供一种可扩展且有效的审计解决方案，推动了智能合约安全的发展，为去中心化应用的安全采用提供了坚实支持。

> Smart contracts are essential to decentralized finance (DeFi) and blockchain ecosystems but are increasingly vulnerable to exploits due to coding errors and complex attack vectors. Traditional static analysis tools and existing vulnerability detection methods often fail to address these challenges comprehensively, leading to high false-positive rates and an inability to detect dynamic vulnerabilities. This paper introduces SmartLLM, a novel approach leveraging fine-tuned LLaMA 3.1 models with Retrieval-Augmented Generation (RAG) to enhance the accuracy and efficiency of smart contract auditing. By integrating domain-specific knowledge from ERC standards and employing advanced techniques such as QLoRA for efficient fine-tuning, SmartLLM achieves superior performance compared to static analysis tools like Mythril and Slither, as well as zero-shot large language model (LLM) prompting methods such as GPT-3.5 and GPT-4. Experimental results demonstrate a perfect recall of 100% and an accuracy score of 70%, highlighting the model's robustness in identifying vulnerabilities, including reentrancy and access control issues. This research advances smart contract security by offering a scalable and effective auditing solution, supporting the secure adoption of decentralized applications.

[Arxiv](https://arxiv.org/abs/2502.13167)