# FDABench：数据智能体的异构数据分析查询基准

发布时间：2025年09月02日

`Agent` `基础理论`

> FDABench: A Benchmark for Data Agents on Analytical Queries over Heterogeneous Data

# 摘要

> 数据驱动决策的需求日益增长，迫切需要能够整合结构化与非结构化数据进行分析的数据代理。尽管数据代理在助力用户完成复杂分析任务方面前景广阔，但该领域仍面临三大关键局限：其一，由于难以设计能评估代理在多源分析任务中各项能力的测试用例，全面的数据代理基准至今缺位；其二，构建融合结构化与非结构化数据的可靠测试用例成本高昂且复杂到难以实现；其三，现有基准的适应性与通用性不足，评估范围因此受限。
  为解决这些挑战，我们提出FDABench——首个专为评估多源数据分析场景中代理能力而设计的数据代理基准。我们的贡献包括：（i）构建了包含2007个多样化任务的标准化基准，覆盖不同数据源、领域、难度等级及任务类型，可全面评估数据代理性能；（ii）设计了代理-专家协作框架，确保在异构数据上可靠高效地构建基准；（iii）为FDABench赋予了跨多种目标系统与框架的强大泛化能力。我们通过FDABench对多种数据代理系统进行评估，结果显示各系统在响应质量、准确性、延迟和令牌成本方面各有优劣。

> The growing demand for data-driven decision-making has created an urgent need for data agents that can integrate structured and unstructured data for analysis. While data agents show promise for enabling users to perform complex analytics tasks, this field still suffers from three critical limitations: first, comprehensive data agent benchmarks remain absent due to the difficulty of designing test cases that evaluate agents' abilities across multi-source analytical tasks; second, constructing reliable test cases that combine structured and unstructured data remains costly and prohibitively complex; third, existing benchmarks exhibit limited adaptability and generalizability, resulting in narrow evaluation scope.
  To address these challenges, we present FDABench, the first data agent benchmark specifically designed for evaluating agents in multi-source data analytical scenarios. Our contributions include: (i) we construct a standardized benchmark with 2,007 diverse tasks across different data sources, domains, difficulty levels, and task types to comprehensively evaluate data agent performance; (ii) we design an agent-expert collaboration framework ensuring reliable and efficient benchmark construction over heterogeneous data; (iii) we equip FDABench with robust generalization capabilities across diverse target systems and frameworks. We use FDABench to evaluate various data agent systems, revealing that each system exhibits distinct advantages and limitations regarding response quality, accuracy, latency, and token cost.

[Arxiv](https://arxiv.org/abs/2509.02473)