# ChemBOMAS：基于LLM增强多智能体系统的化学领域加速贝叶斯优化

发布时间：2025年09月10日

`Agent` `医疗健康`

> ChemBOMAS: Accelerated BO in Chemistry with LLM-Enhanced Multi-Agent System

# 摘要

> 贝叶斯优化（BO）在化学研究中的效率，常因实验数据稀疏、反应机理复杂而受限。为此，我们提出了ChemBOMAS——一种基于大型语言模型（LLM）的多智能体系统框架，旨在加速化学领域的BO优化。该框架借助LLM增强优化过程，协同采用两种策略：知识驱动的粗粒度优化与数据驱动的细粒度优化。首先，在知识驱动阶段，LLM通过推理现有化学知识，智能分解庞大的搜索空间，定位出具有潜力的候选区域；随后，在数据驱动阶段，LLM在这些区域内生成伪数据点，进一步提升BO的数据利用率与收敛速度。基准测试表明，与其他BO算法相比，ChemBOMAS的优化效果和效率均显著提升。更重要的是，我们依据制药行业标准开展湿实验，针对一个此前未报道的复杂化学反应进行条件优化，验证了ChemBOMAS的实际应用价值。实验结果显示，ChemBOMAS的最优目标值达96%，远超领域专家15%的水平。这种实际应用的成功，加之其在基准测试中的出色表现，充分证明ChemBOMAS是加速化学发现的有力工具。

> The efficiency of Bayesian optimization (BO) in chemistry is often hindered by sparse experimental data and complex reaction mechanisms. To overcome these limitations, we introduce ChemBOMAS, a new framework named LLM-Enhanced Multi-Agent System for accelerating BO in chemistry. ChemBOMAS's optimization process is enhanced by LLMs and synergistically employs two strategies: knowledge-driven coarse-grained optimization and data-driven fine-grained optimization. First, in the knowledge-driven coarse-grained optimization stage, LLMs intelligently decompose the vast search space by reasoning over existing chemical knowledge to identify promising candidate regions. Subsequently, in the data-driven fine-grained optimization stage, LLMs enhance the BO process within these candidate regions by generating pseudo-data points, thereby improving data utilization efficiency and accelerating convergence. Benchmark evaluations** further confirm that ChemBOMAS significantly enhances optimization effectiveness and efficiency compared to various BO algorithms. Importantly, the practical utility of ChemBOMAS was validated through wet-lab experiments conducted under pharmaceutical industry protocols, targeting conditional optimization for a previously unreported and challenging chemical reaction. In the wet experiment, ChemBOMAS achieved an optimal objective value of 96%. This was substantially higher than the 15% achieved by domain experts. This real-world success, together with strong performance on benchmark evaluations, highlights ChemBOMAS as a powerful tool to accelerate chemical discovery.

[Arxiv](https://arxiv.org/abs/2509.08736)