# CoE-Ops: 专为AIOps问答量身打造的LLM专家协作平台

发布时间：2025年07月25日

`LLM应用` `AIOps` `DevOps`

> CoE-Ops: Collaboration of LLM-based Experts for AIOps Question-Answering

# 摘要

> 人工智能的迅猛发展催生了AIOps这一引人注目的DevOps范式。尽管已有大量研究致力于提升AIOps各阶段的性能，但受限于领域知识，单一模型仅能处理特定任务，如日志解析与根本原因分析。然而，结合多个模型的集成方法已被证明能显著提升效果，这一点在集成学习与近期LLMs训练中均有体现。为应对AIOps中的类似挑战，本文提出了一种结合通用LLM任务分类器的专家协作框架（CoE-Ops），并引入检索增强生成机制，以提升其在处理高水平（如代码、构建、测试等）与低水平（如故障分析、异常检测等）问答任务中的能力。实验结果表明，CoE-Ops在DevOps-EVAL数据集上表现优异：相比现有CoE方法，其在高水平AIOps任务的路由准确性方面提升了72%；在DevOps问题解决方面，相比单一AIOps模型，准确率提高了8%；在与更大规模的专家混合模型（MoE）相比，准确率提高了14%。

> With the rapid evolution of artificial intelligence, AIOps has emerged as a prominent paradigm in DevOps. Lots of work has been proposed to improve the performance of different AIOps phases. However, constrained by domain-specific knowledge, a single model can only handle the operation requirement of a specific task,such as log parser,root cause analysis. Meanwhile, combining multiple models can achieve more efficient results, which have been proved in both previous ensemble learning and the recent LLM training domain. Inspired by these works,to address the similar challenges in AIOPS, this paper first proposes a collaboration-of-expert framework(CoE-Ops) incorporating a general-purpose large language model task classifier. A retrieval-augmented generation mechanism is introduced to improve the framework's capability in handling both Question-Answering tasks with high-level(Code,build,Test,etc.) and low-level(fault analysis,anomaly detection,etc.). Finally, the proposed method is implemented in the AIOps domain, and extensive experiments are conducted on the DevOps-EVAL dataset. Experimental results demonstrate that CoE-Ops achieves a 72% improvement in routing accuracy for high-level AIOps tasks compared to existing CoE methods, delivers up to 8% accuracy enhancement over single AIOps models in DevOps problem resolution, and outperforms larger-scale Mixture-of-Experts (MoE) models by up to 14% in accuracy.

[Arxiv](https://arxiv.org/abs/2507.22937)