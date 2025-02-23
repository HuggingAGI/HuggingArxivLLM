# CORBA：基于大型语言模型的多智能体系统中的传染性递归阻塞攻击

发布时间：2025年02月20日

`Agent` `多智能体系统` `人工智能`

> CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models

# 摘要

> 基于大语言模型的多智能体系统（LLM-MASs）在复杂任务协作中表现出色，尽管这些系统内置了安全机制，例如通过校准拒绝有害指令，但其安全性仍存在重大研究空白，使系统易受定向攻击。本文提出了一种名为传染性递归阻塞攻击（Corba）的新型攻击手段，该方法简单却极具破坏性，能够扰乱LLM-MAS中智能体间的交互。Corba的两大核心特性使其威力倍增：其传染性使其能在任意网络拓扑中快速传播，而其递归性则可导致计算资源持续耗尽。特别值得注意的是，这些阻塞攻击往往以看似无害的指令形式出现，这使得传统的校准方法难以有效应对。我们在AutoGen和Camel这两个广泛应用的LLM-MAS系统上对Corba进行了全面评估，覆盖了多种网络拓扑和商业模型。此外，我们还在开放式的交互式LLM-MAS环境中进行了更深入的实验，进一步验证了Corba在复杂拓扑结构和开源模型中的显著效果。我们的实验代码已开源，地址为：https://github.com/zhrli324/Corba。

> Large Language Model-based Multi-Agent Systems (LLM-MASs) have demonstrated remarkable real-world capabilities, effectively collaborating to complete complex tasks. While these systems are designed with safety mechanisms, such as rejecting harmful instructions through alignment, their security remains largely unexplored. This gap leaves LLM-MASs vulnerable to targeted disruptions. In this paper, we introduce Contagious Recursive Blocking Attacks (Corba), a novel and simple yet highly effective attack that disrupts interactions between agents within an LLM-MAS. Corba leverages two key properties: its contagious nature allows it to propagate across arbitrary network topologies, while its recursive property enables sustained depletion of computational resources. Notably, these blocking attacks often involve seemingly benign instructions, making them particularly challenging to mitigate using conventional alignment methods. We evaluate Corba on two widely-used LLM-MASs, namely, AutoGen and Camel across various topologies and commercial models. Additionally, we conduct more extensive experiments in open-ended interactive LLM-MASs, demonstrating the effectiveness of Corba in complex topology structures and open-source models. Our code is available at: https://github.com/zhrli324/Corba.

[Arxiv](https://arxiv.org/abs/2502.14529)