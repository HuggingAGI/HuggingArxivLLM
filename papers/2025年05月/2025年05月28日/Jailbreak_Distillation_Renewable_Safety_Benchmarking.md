# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月28日

`LLM应用

摘要中提到的Jailbreak蒸馏框架专注于构建安全基准来评估和提升大型语言模型的安全性，属于应用层面的研究，因此归类为LLM应用。` `人工智能`

> Jailbreak Distillation: Renewable Safety Benchmarking

# 摘要

> 大型语言模型（LLMs）在关键应用中的快速部署，凸显了建立稳健安全基准的迫切需求。为此，我们提出了Jailbreak蒸馏（JBDistill）——一种创新的基准构建框架，通过将越狱攻击转化为高质量且易于更新的安全基准，为LLMs的安全评估提供了全新思路。JBDistill采用少量开发模型和现有越狱攻击算法，构建候选提示池，并运用提示选择算法筛选出高效提示子集作为安全基准。这一方法不仅确保了跨模型评估的一致性，从而实现公平对比和结果可重复，还大幅降低了更新基准所需的人力成本，有效缓解了数据饱和和污染问题。实验结果表明，JBDistill在13种多样化保留模型上展现出强大的鲁棒性，涵盖专有、专业及新一代LLMs。与现有安全基准相比，JBDistill不仅保持了高可分性和多样性，更在有效性上实现了显著提升。因此，JBDistill为安全评估提供了一个高效、可持续且灵活的解决方案。

> Large language models (LLMs) are rapidly deployed in critical applications, raising urgent needs for robust safety benchmarking. We propose Jailbreak Distillation (JBDistill), a novel benchmark construction framework that "distills" jailbreak attacks into high-quality and easily-updatable safety benchmarks. JBDistill utilizes a small set of development models and existing jailbreak attack algorithms to create a candidate prompt pool, then employs prompt selection algorithms to identify an effective subset of prompts as safety benchmarks. JBDistill addresses challenges in existing safety evaluation: the use of consistent evaluation prompts across models ensures fair comparisons and reproducibility. It requires minimal human effort to rerun the JBDistill pipeline and produce updated benchmarks, alleviating concerns on saturation and contamination. Extensive experiments demonstrate our benchmarks generalize robustly to 13 diverse evaluation models held out from benchmark construction, including proprietary, specialized, and newer-generation LLMs, significantly outperforming existing safety benchmarks in effectiveness while maintaining high separability and diversity. Our framework thus provides an effective, sustainable, and adaptable solution for streamlining safety evaluation.

[Arxiv](https://arxiv.org/abs/2505.22037)