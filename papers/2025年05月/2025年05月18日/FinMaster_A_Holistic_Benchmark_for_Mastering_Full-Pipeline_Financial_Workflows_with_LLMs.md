# FinMaster: 基于大语言模型的全方位基准测试，助力全面驾驭完整金融工作流

发布时间：2025年05月18日

`LLM应用`

> FinMaster: A Holistic Benchmark for Mastering Full-Pipeline Financial Workflows with LLMs

# 摘要

> 金融任务对全球经济稳定至关重要，但其执行面临流程繁琐、容错率低、数据分散及工具局限性等多重挑战。大型语言模型（LLMs）在自然语言处理领域表现优异，并展现出通过推理和上下文理解来自动化工作流程的潜力。然而，现有金融领域的LLMs评估基准存在不足：领域特定数据缺乏、任务设计简单且评估框架不完整。为解决这些问题，本文提出FinMaster，这是一个全面的金融基准测试，旨在系统性评估LLMs在财务素养、会计、审计和咨询等领域的的能力。具体而言，FinMaster包含三个主要模块：i) FinSim，构建生成合成的、符合隐私要求的公司财务数据的模拟器，以复制市场动态；ii) FinSuite，提供核心金融领域的任务，涵盖183个不同类型和难度的任务；iii) FinEval，开发一个统一的评估界面。对当前先进的LLMs进行的广泛实验揭示了在金融推理方面的能力差距，准确率从基础任务的90%以上降至需要多步骤推理的复杂场景的40%。这种下降趋势显示出计算错误的传播，其中单指标计算最初展示出58%的准确率，但在多指标场景中下降至37%。据我们所知，FinMaster是第一个涵盖完整金融工作流程且包含具有挑战性任务的基准测试。我们希望FinMaster能够架起学术界与金融实务界的桥梁，推动LLMs在现实金融实践中的应用，从而提升效率和准确性。


> Financial tasks are pivotal to global economic stability; however, their execution faces challenges including labor intensive processes, low error tolerance, data fragmentation, and tool limitations. Although large language models (LLMs) have succeeded in various natural language processing tasks and have shown potential in automating workflows through reasoning and contextual understanding, current benchmarks for evaluating LLMs in finance lack sufficient domain-specific data, have simplistic task design, and incomplete evaluation frameworks. To address these gaps, this article presents FinMaster, a comprehensive financial benchmark designed to systematically assess the capabilities of LLM in financial literacy, accounting, auditing, and consulting. Specifically, FinMaster comprises three main modules: i) FinSim, which builds simulators that generate synthetic, privacy-compliant financial data for companies to replicate market dynamics; ii) FinSuite, which provides tasks in core financial domains, spanning 183 tasks of various types and difficulty levels; and iii) FinEval, which develops a unified interface for evaluation. Extensive experiments over state-of-the-art LLMs reveal critical capability gaps in financial reasoning, with accuracy dropping from over 90% on basic tasks to merely 40% on complex scenarios requiring multi-step reasoning. This degradation exhibits the propagation of computational errors, where single-metric calculations initially demonstrating 58% accuracy decreased to 37% in multimetric scenarios. To the best of our knowledge, FinMaster is the first benchmark that covers full-pipeline financial workflows with challenging tasks. We hope that FinMaster can bridge the gap between research and industry practitioners, driving the adoption of LLMs in real-world financial practices to enhance efficiency and accuracy.

[Arxiv](https://arxiv.org/abs/2505.13533)