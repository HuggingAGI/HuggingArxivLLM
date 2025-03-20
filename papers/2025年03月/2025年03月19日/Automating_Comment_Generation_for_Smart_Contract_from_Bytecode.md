# # 自动化生成智能合约注释：基于字节码的方法

发布时间：2025年03月19日

`LLM应用

理由：该论文探讨了如何利用大型语言模型（LLM）从智能合约的字节码生成自然语言摘要，属于LLM的实际应用。` `软件工程`

> Automating Comment Generation for Smart Contract from Bytecode

# 摘要

> 近年来，智能合约在自动金融和商业交易中发挥着关键作用。为了帮助非编程背景的用户更好地理解智能合约逻辑，先前研究提出了将智能合约源代码自动翻译为代码摘要的模型。然而，仅有13%的以太坊智能合约附带源代码，这大大限制了现有工具的实际应用。鉴于部署智能合约时字节码不可或缺，本文首次提出从字节码自动生成智能合约代码摘要的任务，并提出了一种名为SmartBT的新方法，可直接将智能合约字节码翻译为精细的自然语言描述。这一任务面临两大挑战：字节码中隐藏的结构化逻辑以及字节码与自然语言描述之间的巨大语义鸿沟。为解决这些挑战，我们将字节码转换为控制流图（CFG）以提取代码结构和逻辑细节，并引入信息检索组件获取相似注释以填补语义鸿沟。基于此，构建了一个注意力机制的序列到序列神经网络模型，并通过复制机制直接复制罕见词汇，同时采用覆盖机制消除重复输出。实验结果表明，SmartBT在自动评估中显著优于基线模型，人工评估也验证了其在直接从字节码生成准确注释方面的有效性与潜力。

> Recently, smart contracts have played a vital role in automatic financial and business transactions. To help end users without programming background to better understand the logic of smart contracts, previous studies have proposed models for automatically translating smart contract source code into their corresponding code summaries. However, in practice, only 13% of smart contracts deployed on the Ethereum blockchain are associated with source code. The practical usage of these existing tools is significantly restricted. Considering that bytecode is always necessary when deploying smart contracts, in this paper, we first introduce the task of automatically generating smart contract code summaries from bytecode. We propose a novel approach, named SmartBT (Smart contract Bytecode Translator) for automatically translating smart contract bytecode into fine-grained natural language description directly. Two key challenges are posed for this task: structural code logic hidden in bytecode and the huge semantic gap between bytecode and natural language descriptions. To address the first challenge, we transform bytecode into CFG (Control-Flow Graph) to learn code structural and logic details. Regarding the second challenge, we introduce an information retrieval component to fetch similar comments for filling the semantic gap. Then the structural input and semantic input are used to build an attentional sequence-to-sequence neural network model. The copy mechanism is employed to copy rare words directly from similar comments and the coverage mechanism is employed to eliminate repetitive outputs. The automatic evaluation results show that SmartBT outperforms a set of baselines by a large margin, and the human evaluation results show the effectiveness and potential of SmartBT in producing meaningful and accurate comments for smart contract code from bytecode directly.

[Arxiv](https://arxiv.org/abs/2503.15270)