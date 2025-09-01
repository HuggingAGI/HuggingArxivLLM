# 参数并非生而平等：巧妙隔离显著提升微调性能

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Not All Parameters Are Created Equal: Smart Isolation Boosts Fine-Tuning Performance

# 摘要

> 监督微调（SFT）是大型语言模型（LLMs）适配下游任务的核心手段，但模型性能常受“跷跷板现象”困扰：不加区分的参数更新虽能让部分任务性能提升，却会牺牲其他任务表现。为此，我们提出了全新的\emph{核心参数隔离微调}（CPI-FT）框架。具体而言，我们首先在各任务上独立微调LLM，通过量化参数更新幅度识别核心参数区域；接着，根据核心区域的重叠程度对任务进行分组，形成集群以开展联合建模。我们还引入了参数融合技术：对每个任务，将其独立微调模型的核心参数直接移植到统一骨干网络；对于不同任务的非核心参数，则通过球面线性插值（SLERP）进行平滑整合，从而减轻破坏性干扰。之后，我们使用混合任务数据进行轻量级流水线SFT训练，同时冻结先前任务的核心区域，避免灾难性遗忘。在多个公共基准上的大量实验证实，我们的方法能有效缓解任务干扰与遗忘问题，性能持续优于常规多任务及多阶段微调基线。

> Supervised fine-tuning (SFT) is a pivotal approach to adapting large language models (LLMs) for downstream tasks; however, performance often suffers from the ``seesaw phenomenon'', where indiscriminate parameter updates yield progress on certain tasks at the expense of others. To address this challenge, we propose a novel \emph{Core Parameter Isolation Fine-Tuning} (CPI-FT) framework. Specifically, we first independently fine-tune the LLM on each task to identify its core parameter regions by quantifying parameter update magnitudes. Tasks with similar core regions are then grouped based on region overlap, forming clusters for joint modeling. We further introduce a parameter fusion technique: for each task, core parameters from its individually fine-tuned model are directly transplanted into a unified backbone, while non-core parameters from different tasks are smoothly integrated via Spherical Linear Interpolation (SLERP), mitigating destructive interference. A lightweight, pipelined SFT training phase using mixed-task data is subsequently employed, while freezing core regions from prior tasks to prevent catastrophic forgetting. Extensive experiments on multiple public benchmarks demonstrate that our approach significantly alleviates task interference and forgetting, consistently outperforming vanilla multi-task and multi-stage fine-tuning baselines.

[Arxiv](https://arxiv.org/abs/2508.21741)