# 因果演化图：重新定义推理中的模型链

发布时间：2025年06月09日

`LLM理论

这篇论文提出了一种新的模型架构GoCE，改进了Transformer在处理因果关系和长程依赖方面的能力，属于大型语言模型的理论研究和架构创新。` `人工智能`

> Graph-of-Causal Evolution: Challenging Chain-of-Model for Reasoning

# 摘要

> 针对链式模型（CoM）中各子链仅依赖前序信息且可能因因果掩码阻断全局上下文流动而导致长程依赖丢失的问题，本研究提出因果演化图（GoCE）。其核心机制是将隐式令牌表示映射为可微分且稀疏的因果邻接矩阵，并通过因果掩码注意力和因果MoE在各层计算中渗透因果约束。结合干预一致性损失测试与自演化门控机制，实现了因果结构学习与Transformer架构自适应更新的动态平衡。研究者基于Claude Sonnet 4、o4-mini-high和DeepSeek R1分别搭建沙盒实验环境，并引入GoCE中的Transformer变体架构进行测试。在CLUTRR、CLADDER、EX-FEVER和CausalQA等公开数据集上进行评估，结果表明GoCE不仅显著提升了Transformer捕捉长程因果依赖的能力，还增强了模型的自演化能力。相较于CoM，GoCE在设计理念上实现了超越，为未来因果学习和持续自适应改进研究提供了重要参考。

> In view of the problem that each subchain in the chain-of-model (CoM) relies only on the information of the previous subchain and may lose long-range dependencies due to the causal mask blocking the global context flow between multi-level subchains, this work proposes a graph of causal evolution (GoCE). Its core principle is to map the implicit token representation into a differentiable and sparse causal adjacency matrix, then permeate causal constraints through each layer of calculation using causal-masked attention and causal-MoE. By combining intervention consistency loss test and self-evolution gate, the dynamic balance between causal structure learning and adaptive updating of transformer architecture is realized. The researcher built experimental environments in sandboxes built with Claude Sonnet 4, o4-mini-high, and DeepSeek R1 respectively with the transformer variant architecture introduced in GoCE. It is evaluated on publicly available datasets including CLUTRR, CLADDER, EX-FEVER, and CausalQA and compared with the baseline LLMs. The finding proves that GoCE strengthens the transformer's ability to capture long-range causal dependencies, while the ability to self-evolve is improved. It not only surpasses the design of CoM in terms of design principles, but also provides experience for future research on causal learning and continuous adaptive improvement.

[Arxiv](https://arxiv.org/abs/2506.07501)