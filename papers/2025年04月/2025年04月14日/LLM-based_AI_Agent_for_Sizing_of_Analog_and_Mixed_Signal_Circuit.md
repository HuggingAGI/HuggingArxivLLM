# 基于 LLM 的 AI 智能体在模拟与混合信号电路设计中的应用

发布时间：2025年04月14日

`LLM应用` `集成电路设计` `电子设计自动化`

> LLM-based AI Agent for Sizing of Analog and Mixed Signal Circuit

# 摘要

> 模拟和混合信号（AMS）集成电路设计通常需要投入大量手动工作，尤其是在晶体管尺寸确定过程中。尽管机器学习技术在电子设计自动化（EDA）中展现出降低复杂性和减少人工干预的潜力，但它们仍面临诸多挑战，如反复迭代和缺乏对AMS电路设计的深入理解。最近，大型语言模型（LLMs）在多个领域展现出巨大潜力，它们在电路设计方面具备一定知识，并有望实现晶体管尺寸确定的自动化。在本研究中，我们提出了一种基于LLMs的AI代理，用于辅助AMS电路设计中的尺寸确定过程。通过将LLMs与外部电路仿真工具和数据分析功能相结合，并运用提示工程策略，该代理成功优化了多个电路，使其达到目标性能指标。我们评估了不同LLMs的性能，以评估它们在七种基本电路中的适用性和优化效果，并从中选择了表现最佳的Claude 3.5 Sonnet模型，进一步在运算放大器上进行探索，该放大器具有互补输入级和AB类输出级。该电路针对九项性能指标进行了评估，我们分别在三个不同的性能需求组别下进行了实验。在达到目标要求方面，我们实现了高达60%的成功率。总体而言，这项工作展示了LLMs在提升AMS电路设计方面的潜力。

> The design of Analog and Mixed-Signal (AMS) integrated circuits (ICs) often involves significant manual effort, especially during the transistor sizing process. While Machine Learning techniques in Electronic Design Automation (EDA) have shown promise in reducing complexity and minimizing human intervention, they still face challenges such as numerous iterations and a lack of knowledge about AMS circuit design. Recently, Large Language Models (LLMs) have demonstrated significant potential across various fields, showing a certain level of knowledge in circuit design and indicating their potential to automate the transistor sizing process. In this work, we propose an LLM-based AI agent for AMS circuit design to assist in the sizing process. By integrating LLMs with external circuit simulation tools and data analysis functions and employing prompt engineering strategies, the agent successfully optimized multiple circuits to achieve target performance metrics. We evaluated the performance of different LLMs to assess their applicability and optimization effectiveness across seven basic circuits, and selected the best-performing model Claude 3.5 Sonnet for further exploration on an operational amplifier, with complementary input stage and class AB output stage. This circuit was evaluated against nine performance metrics, and we conducted experiments under three distinct performance requirement groups. A success rate of up to 60% was achieved for reaching the target requirements. Overall, this work demonstrates the potential of LLMs to improve AMS circuit design.

[Arxiv](https://arxiv.org/abs/2504.11497)