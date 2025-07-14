# KG-Attention: 基于知识图谱引导的测试时注意力机制，通过双向信息聚合实现

发布时间：2025年07月11日

`LLM应用

这篇论文探讨了如何通过知识图谱（KGs）来提升大型语言模型（LLMs）的性能，特别是在测试时动态融合知识而不改变模型参数。该方法通过引入知识图谱引导注意力（KGA）模块，优化了知识融合过程，属于LLM应用层面的研究。` `知识图谱`

> KG-Attention: Knowledge Graph-Guided Attention at Test-Time via Bidirectional Information Aggregation

# 摘要

> 知识图谱（KGs）在提升大型语言模型（LLMs）性能中起着关键作用，通过将结构化且具象化的知识引入学习过程。然而，现有的大多数KG增强方法都依赖于参数密集型微调，这不仅面临灾难性遗忘的风险，还可能损害预训练模型的泛化能力。此外，由于其静态集成框架，它们在实时知识更新方面表现出有限的适应性。为了解决这些问题，我们引入了首个专为LLMs设计的测试时KG增强框架，该框架围绕一个专用的知识图谱引导注意力（KGA）模块构建，能够在不更新任何参数的情况下实现动态知识融合。所提出的KGA模块通过两条协同作用的通路增强了标准的自注意力机制：向外聚合和向内聚合。具体而言，向外通路通过输入驱动的KG融合，动态地将外部知识整合到输入表示中。而向内聚合则通过KG引导的过滤器对输入表示进行精炼，抑制与任务无关的信号并放大与知识相关联的模式。重要的是，当向外通路处理知识融合时，向内通路会筛选出最相关的三元组，并将其反馈到融合过程中，形成一个闭环增强机制。通过协同结合这两条通路，所提出的方法在不进行任何参数修改的情况下，支持仅在测试时进行实时知识融合。在五个基准测试上的广泛实验验证了KGA在知识融合性能上与现有方法相比具有可比性。

> Knowledge graphs (KGs) play a critical role in enhancing large language models (LLMs) by introducing structured and grounded knowledge into the learning process. However, most existing KG-enhanced approaches rely on parameter-intensive fine-tuning, which risks catastrophic forgetting and degrades the pretrained model's generalization. Moreover, they exhibit limited adaptability to real-time knowledge updates due to their static integration frameworks. To address these issues, we introduce the first test-time KG-augmented framework for LLMs, built around a dedicated knowledge graph-guided attention (KGA) module that enables dynamic knowledge fusion without any parameter updates. The proposed KGA module augments the standard self-attention mechanism with two synergistic pathways: outward and inward aggregation. Specifically, the outward pathway dynamically integrates external knowledge into input representations via input-driven KG fusion. This inward aggregation complements the outward pathway by refining input representations through KG-guided filtering, suppressing task-irrelevant signals and amplifying knowledge-relevant patterns. Importantly, while the outward pathway handles knowledge fusion, the inward path selects the most relevant triples and feeds them back into the fusion process, forming a closed-loop enhancement mechanism. By synergistically combining these two pathways, the proposed method supports real-time knowledge fusion exclusively at test-time, without any parameter modification. Extensive experiments on five benchmarks verify the comparable knowledge fusion performance of KGA.

[Arxiv](https://arxiv.org/abs/2507.08704)