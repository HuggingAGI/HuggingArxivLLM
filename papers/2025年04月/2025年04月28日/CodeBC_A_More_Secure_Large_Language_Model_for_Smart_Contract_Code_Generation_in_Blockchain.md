# # CodeBC：专为区块链智能合约代码生成设计的更安全大型语言模型

发布时间：2025年04月28日

`LLM应用` `区块链` `软件工程`

> CodeBC: A More Secure Large Language Model for Smart Contract Code Generation in Blockchain

# 摘要

> 大型语言模型（LLMs）擅长将自然语言转化为代码，但在安全漏洞的理解上仍有欠缺，尤其在区块链智能合约开发等高安全场景中，这限制了其生成安全代码的能力。研究者曾尝试通过训练模型区分漏洞代码与修复代码来提升其安全意识，但这种方法依赖于人工标注的漏洞数据，这类数据仅在Python和C++等主流语言中存在。对于Solidity等资源匮乏的语言，大规模标注数据稀缺且难以获取。为解决这一难题，我们推出了CodeBC，一个专为区块链安全智能合约设计的代码生成模型。CodeBC基于CodeLlama采用三阶段微调策略，与传统方法不同，它无需依赖成对的漏洞位置标注，而是通过漏洞和安全标签让模型学习安全与非安全代码的区别。在推理过程中，模型借助安全标签生成安全可靠的代码。实验数据显示，CodeBC在BLEU、CodeBLEU和编译成功率上均超越了基线模型，同时大幅降低了漏洞率。这证明了我们三阶段微调策略的有效性和经济性，使CodeBC成为生成安全智能合约代码的有力工具。


> Large language models (LLMs) excel at generating code from natural language instructions, yet they often lack an understanding of security vulnerabilities. This limitation makes it difficult for LLMs to avoid security risks in generated code, particularly in high-security programming tasks such as smart contract development for blockchain. Researchers have attempted to enhance the vulnerability awareness of these models by training them to differentiate between vulnerable and fixed code snippets. However, this approach relies heavily on manually labeled vulnerability data, which is only available for popular languages like Python and C++. For low-resource languages like Solidity, used in smart contracts, large-scale annotated datasets are scarce and difficult to obtain. To address this challenge, we introduce CodeBC, a code generation model specifically designed for generating secure smart contracts in blockchain. CodeBC employs a three-stage fine-tuning approach based on CodeLlama, distinguishing itself from previous methods by not relying on pairwise vulnerability location annotations. Instead, it leverages vulnerability and security tags to teach the model the differences between vulnerable and secure code. During the inference phase, the model leverages security tags to generate secure and robust code. Experimental results demonstrate that CodeBC outperforms baseline models in terms of BLEU, CodeBLEU, and compilation pass rates, while significantly reducing vulnerability rates. These findings validate the effectiveness and cost-efficiency of our three-stage fine-tuning strategy, making CodeBC a promising solution for generating secure smart contract code.

[Arxiv](https://arxiv.org/abs/2504.21043)