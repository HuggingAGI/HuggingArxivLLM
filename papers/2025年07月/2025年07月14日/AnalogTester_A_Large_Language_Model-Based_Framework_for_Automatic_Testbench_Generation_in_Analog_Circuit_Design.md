# # AnalogTester：基于大型语言模型的模拟电路自动测试台生成框架

发布时间：2025年07月14日

`LLM应用` `模拟电路设计` `自动化设计`

> AnalogTester: A Large Language Model-Based Framework for Automatic Testbench Generation in Analog Circuit Design

# 摘要

> 大型语言模型（LLMs）在模拟电路设计领域展现出巨大潜力，但测试台构建仍依赖手动操作，成为实现全流程自动化设计的关键瓶颈。特别是从学术论文复现电路设计时，手动构建测试台不仅耗时且需要频繁调整，难以满足自动化所需的多样性和灵活性需求。AnalogTester 通过一个LLM驱动的流水线解决这一难题，包含四个关键环节：a) 领域知识整合，b) 论文信息提取，c) 仿真方案合成，d) 与清华电子设计（TED）结合的测试台代码生成。AnalogTester 已成功实现对运算放大器（op-amps）、带隙基准源（BGRs）和低压差线性稳压器（LDOs）这三类基础模拟电路的自动化测试台构建，并保持了框架的可扩展性以适应更多电路拓扑。此外，它还能生成电路知识数据与TED代码语料库，为LLM在模拟电路设计自动化领域的专业化训练奠定了基础数据集。

> Recent advancements have demonstrated the significant potential of large language models (LLMs) in analog circuit design. Nevertheless, testbench construction for analog circuits remains manual, creating a critical bottleneck in achieving fully automated design processes. Particularly when replicating circuit designs from academic papers, manual Testbench construction demands time-intensive implementation and frequent adjustments, which fails to address the dynamic diversity and flexibility requirements for automation. AnalogTester tackles automated analog design challenges through an LLM-powered pipeline: a) domain-knowledge integration, b) paper information extraction, c) simulation scheme synthesis, and d) testbench code generation with Tsinghua Electronic Design (TED). AnalogTester has demonstrated automated Testbench generation capabilities for three fundamental analog circuit types: operational amplifiers (op-amps), bandgap references (BGRs), and low-dropout regulators (LDOs), while maintaining a scalable framework for adaptation to broader circuit topologies. Furthermore, AnalogTester can generate circuit knowledge data and TED code corpus, establishing fundamental training datasets for LLM specialization in analog circuit design automation.

[Arxiv](https://arxiv.org/abs/2507.09965)