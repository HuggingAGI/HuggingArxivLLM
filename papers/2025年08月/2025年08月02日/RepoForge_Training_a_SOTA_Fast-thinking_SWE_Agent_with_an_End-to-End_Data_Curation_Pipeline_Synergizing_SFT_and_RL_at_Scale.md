# 代码库重构：通过构建一个端到端的数据整理流水线，结合监督微调和强化学习在大规模下协作，训练一个最先进的快速思考软件工程师代理。

发布时间：2025年08月02日

`Agent` `软件工程` `人工智能`

> RepoForge: Training a SOTA Fast-thinking SWE Agent with an End-to-End Data Curation Pipeline Synergizing SFT and RL at Scale

# 摘要

> 训练软件工程（SWE）的大型语言模型（LLM）面临诸多瓶颈：昂贵的基础设施、低效的评估流程、稀缺的训练数据以及高昂的质量控制成本。我们推出RepoForge——一个自主的端到端流水线系统，能够大规模生成、评估并训练SWE智能体。我们的核心贡献包括：(1) RepoForge-8B-Agent在SWE-Bench-Verified~\citep{swebench_verified2024}上达到17.4\%的性能，为≤8B的非思考型LLM树立了新标杆；(2) 从真实GitHub提交中自动生成7,304个可执行环境，完全无需人工干预；(3) 通过智能依赖管理和镜像优化，实现14倍存储压缩（每实例从1.4GB降至102MB）；(4) 借助Ray驱动的分布式RepoForge框架，评估速度提升超过70\%；(5) 通过自动化SPICE~\citep{spice2024}难度评估技术，标注成本降低19,000倍。通过整合存储高效的沙箱环境、Ray驱动的评估框架、自动化数据生成、基于SPICE的标注以及无循环的RL架构，我们证明即使是≤8B的模型也能在SWE-Bench-Verified等高要求基准测试中达到新标杆性能。我们的方法有效解决了SWE智能体训练中的关键瓶颈，包括容器化评估的高昂存储成本、低效的顺序奖励流程、高质量训练数据的匮乏、昂贵的手动标注以及多轮RL流水线的性能瓶颈。

> Training software engineering (SWE) LLMs is bottlenecked by expensive infrastructure, inefficient evaluation pipelines, scarce training data, and costly quality control. We present RepoForge, an autonomous, end-to-end pipeline that generates, evaluates, and trains SWE agents at scale. Our key contributions include: (1) RepoForge-8B-Agent, achieving 17.4\% on SWE-Bench-Verified~\citep{swebench_verified2024}, establishing new state-of-the-art for $\leq$8B non-thinking LLMs; (2) 7,304 executable environments auto-generated from real GitHub commits with zero manual intervention; (3) 14$\times$ storage reduction (1.4GB $\rightarrow$ 102MB per instance) via intelligent dependency management and image pruning; (4) $>$70\% faster evaluation using a Ray-powered~\citep{ray2018} distributed RepoForge harness; (5) 19,000$\times$ cheaper labeling through our automated SPICE~\citep{spice2024} difficulty assessment technique. By unifying storage-efficient sandboxing, Ray-powered evaluation harness, automated data generation, SPICE-based labeling, and bubble-free RL scaffold, we demonstrate that even $\leq$8B models can reach new state-of-the-art performance on demanding benchmarks like SWE-Bench-Verified. Our approach addresses critical bottlenecks in SWE agent training: high storage costs of container-based evaluation, inefficient sequential reward pipelines, limited availability of high-quality training data, expensive manual labeling, and multi-turn RL pipeline bottlenecks.

[Arxiv](https://arxiv.org/abs/2508.01550)