# 大型语言模型助力智能合约反编译

发布时间：2025年06月24日

`LLM应用` `区块链` `智能合约安全`

> Decompiling Smart Contracts with a Large Language Model

# 摘要

> 区块链浏览器如 Etherscan 上的智能合约开源率极低，尽管以太坊上部署了 78,047,845 个智能合约（截至 2025 年 5 月 26 日），但仅有 767,520 个（<1%）是开源的。这种不透明性严重威胁着区块链的安全性，亟需对链上智能合约字节码进行自动化的语义分析，这是一项基础性的研究挑战，对识别漏洞和理解恶意行为具有重要意义。

现有的反编译器在将字节码反编译为可读代码方面表现不佳，生成的代码往往复杂难懂，严重阻碍了漏洞分析，并使得解析合约功能以进行安全审计变得困难。

本文提出了一种开创性的反编译流水线，首次成功利用大型语言模型（LLMs）将以太坊虚拟机（EVM）字节码转换为人类可读且语义忠实的 Solidity 代码。我们的方法创新性地采用严格的静态程序分析，将字节码转换为结构化的三地址码（TAC）表示形式。这一中间表示随后引导一个经过专门微调的 Llama-3.2-3B 模型，该模型基于包含 238,446 个 TAC 到 Solidity 函数对的全面数据集进行训练，生成高质量的 Solidity 代码。这种方法的独特优势在于能够恢复有意义的变量名称、复杂的控制流以及精确的函数签名。

通过广泛的实证评估，我们的方法在语义相似度和可读性方面实现了对传统反编译器的重大突破，与原始源代码的平均语义相似度达到 0.82，并且显著提升了代码的可读性。我们的研究成果已经在公开可用的系统中实现，用户可以访问 https://evmdecompiler.com 体验这一技术。


> The widespread lack of broad source code verification on blockchain explorers such as Etherscan, where despite 78,047,845 smart contracts deployed on Ethereum (as of May 26, 2025), a mere 767,520 (< 1%) are open source, presents a severe impediment to blockchain security. This opacity necessitates the automated semantic analysis of on-chain smart contract bytecode, a fundamental research challenge with direct implications for identifying vulnerabilities and understanding malicious behavior. Prevailing decompilers struggle to reverse bytecode in a readable manner, often yielding convoluted code that critically hampers vulnerability analysis and thwarts efforts to dissect contract functionalities for security auditing.
  This paper addresses this challenge by introducing a pioneering decompilation pipeline that, for the first time, successfully leverages Large Language Models (LLMs) to transform Ethereum Virtual Machine (EVM) bytecode into human-readable and semantically faithful Solidity code. Our novel methodology first employs rigorous static program analysis to convert bytecode into a structured three-address code (TAC) representation. This intermediate representation then guides a Llama-3.2-3B model, specifically fine-tuned on a comprehensive dataset of 238,446 TAC-to-Solidity function pairs, to generate high-quality Solidity. This approach uniquely recovers meaningful variable names, intricate control flow, and precise function signatures. Our extensive empirical evaluation demonstrates a significant leap beyond traditional decompilers, achieving an average semantic similarity of 0.82 with original source and markedly superior readability. The practical viability and effectiveness of our research are demonstrated through its implementation in a publicly accessible system, available at https://evmdecompiler.com.

[Arxiv](https://arxiv.org/abs/2506.19624)