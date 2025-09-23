# EngiBench：评估大型语言模型工程问题解决能力的基准测试

发布时间：2025年09月22日

`LLM应用` `工业与制造`

> EngiBench: A Benchmark for Evaluating Large Language Models on Engineering Problem Solving

# 摘要

> 大型语言模型（LLMs）在条件明确时已展现出卓越的数学推理能力。然而，现实世界的工程问题远不止数学符号计算——还需应对不确定性、复杂上下文和开放式场景。现有基准难以涵盖这些复杂特性。为此，我们提出EngiBench——一个用于评估LLMs工程问题求解能力的分层基准。该基准包含三个难度递增的层级（基础知识检索、多步骤上下文推理、开放式建模），并覆盖多个工程子领域。为深入理解模型表现，我们将每个问题系统改写为三种受控变体（扰动版、知识增强版、数学抽象版），以便分别评估模型的鲁棒性、领域知识掌握度和数学推理能力。实验结果显示，模型性能在不同层级间存在显著差距：任务难度越高，模型表现越差；问题稍有扰动，性能便明显下降；而在高级别工程任务上，模型表现远不及人类专家。这些结果表明，当前LLMs仍缺乏解决现实工程问题所需的高级推理能力，凸显了未来需研发具备更深层次、更可靠问题求解能力模型的必要性。相关源代码和数据已开源，地址为https://github.com/EngiBench/EngiBench。

> Large language models (LLMs) have shown strong performance on mathematical reasoning under well-posed conditions. However, real-world engineering problems require more than mathematical symbolic computation -- they need to deal with uncertainty, context, and open-ended scenarios. Existing benchmarks fail to capture these complexities. We introduce EngiBench, a hierarchical benchmark designed to evaluate LLMs on solving engineering problems. It spans three levels of increasing difficulty (foundational knowledge retrieval, multi-step contextual reasoning, and open-ended modeling) and covers diverse engineering subfields. To facilitate a deeper understanding of model performance, we systematically rewrite each problem into three controlled variants (perturbed, knowledge-enhanced, and math abstraction), enabling us to separately evaluate the model's robustness, domain-specific knowledge, and mathematical reasoning abilities. Experiment results reveal a clear performance gap across levels: models struggle more as tasks get harder, perform worse when problems are slightly changed, and fall far behind human experts on the high-level engineering tasks. These findings reveal that current LLMs still lack the high-level reasoning needed for real-world engineering, highlighting the need for future models with deeper and more reliable problem-solving capabilities. Our source code and data are available at https://github.com/EngiBench/EngiBench.

[Arxiv](https://arxiv.org/abs/2509.17677)