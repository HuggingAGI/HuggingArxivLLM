# 从评估到增强：大型语言模型助力零知识证明代码生成

发布时间：2025年09月15日

`Agent` `金融科技`

> From Evaluation to Enhancement: Large Language Models for Zero-Knowledge Proof Code Generation

# 摘要

> 零知识证明（ZKPs）正日益应用于隐私保护认证、区块链可扩展性及安全金融等领域。然而，编写ZK程序仍颇具挑战：与主流编程不同，ZK开发需涉及有限域算术、约束系统及组件的推理，这使其成为知识密集型且易出错的工作。尽管大型语言模型（LLMs）在通用语言中已展现出强大的代码生成能力，但在ZK编程中——其正确性取决于语言掌握与组件级推理能力的双重保障——LLMs的有效性尚未得到探索。为填补这一空白，我们提出	extsc{ZK-Eval}——一个特定领域的评估框架，从语言知识、组件能力和端到端程序生成三个层面探究LLM的能力。我们对四款最先进LLM的评估显示，这些模型在表层语法上表现出色，但在组件使用和语义正确性方面存在不足，常生成错误程序。基于这些发现，我们引入	extsc{ZK-Coder}——一个智能体框架，通过约束草图绘制、引导式检索和交互式修复来增强LLM的能力。在Circom和Noir上的实验结果显示显著提升，成功率分别从17.35%提升至83.38%和从32.21%提升至90.05%。借助	extsc{ZK-Eval}和	extsc{ZK-Coder}，我们为系统衡量和增强LLM在ZK代码生成中的性能奠定了基础，旨在降低从业者的使用门槛并推动可信计算的发展。

> Zero-knowledge proofs (ZKPs) are increasingly deployed in domains such as privacy-preserving authentication, blockchain scalability, and secure finance. However, authoring ZK programs remains challenging: unlike mainstream programming, ZK development requires reasoning about finite field arithmetic, constraint systems, and gadgets, making it knowledge-intensive and error-prone. While large language models (LLMs) have demonstrated strong code generation capabilities in general-purpose languages, their effectiveness for ZK programming, where correctness hinges on both language mastery and gadget-level reasoning, remains unexplored. To address this gap, we propose \textsc{ZK-Eval}, a domain-specific evaluation pipeline that probes LLM capabilities at three levels: language knowledge, gadget competence, and end-to-end program generation. Our evaluation of four state-of-the-art LLMs reveals that models excel at surface-level syntax but struggle with gadget usage and semantic correctness, often yielding incorrect programs. Based on these insights, we introduce \textsc{ZK-Coder}, an agentic framework that augments LLMs with constraint sketching, guided retrieval, and interactive repair. Experiments on Circom and Noir show substantial gains, with success rates improving from 17.35\% to 83.38\% and from 32.21\% to 90.05\%, respectively. With \textsc{ZK-Eval} and \textsc{ZK-Coder}, we establish a foundation for systematically measuring and augmenting LLMs in ZK code generation to lower barriers for practitioners and advance trustworthy computation.

[Arxiv](https://arxiv.org/abs/2509.11708)