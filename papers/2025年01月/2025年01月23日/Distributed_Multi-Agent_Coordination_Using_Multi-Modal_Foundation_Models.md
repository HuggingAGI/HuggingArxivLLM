# 基于多模态基础模型的分布式多智能体协调

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了如何利用大型多模态基础模型（LFMs）来自动生成约束，并设计了一系列智能体原型来解决分布式约束优化问题（DCOPs）。论文的核心内容围绕智能体的设计和应用，因此应归类为Agent。` `多智能体系统` `约束优化`

> Distributed Multi-Agent Coordination Using Multi-Modal Foundation Models

# 摘要

> 分布式约束优化问题（DCOPs）为多智能体协调提供了强大框架，但传统方法依赖手动构建，费时费力。为此，我们提出了VL-DCOPs框架，利用大型多模态基础模型（LFMs）从视觉和语言指令中自动生成约束。我们设计了一系列智能体原型来解决VL-DCOPs：从部分依赖LFM的神经符号智能体，到完全依赖LFM的全神经智能体。我们在三个新的VL-DCOP任务上，使用前沿的LLMs和VLMs对这些智能体进行评估，并对比其优缺点。最后，我们探讨了该研究如何推动DCOP领域应对更广泛的挑战。

> Distributed Constraint Optimization Problems (DCOPs) offer a powerful framework for multi-agent coordination but often rely on labor-intensive, manual problem construction. To address this, we introduce VL-DCOPs, a framework that takes advantage of large multimodal foundation models (LFMs) to automatically generate constraints from both visual and linguistic instructions. We then introduce a spectrum of agent archetypes for solving VL-DCOPs: from a neuro-symbolic agent that delegates some of the algorithmic decisions to an LFM, to a fully neural agent that depends entirely on an LFM for coordination. We evaluate these agent archetypes using state-of-the-art LLMs (large language models) and VLMs (vision language models) on three novel VL-DCOP tasks and compare their respective advantages and drawbacks. Lastly, we discuss how this work extends to broader frontier challenges in the DCOP literature.

[Arxiv](https://arxiv.org/abs/2501.14189)