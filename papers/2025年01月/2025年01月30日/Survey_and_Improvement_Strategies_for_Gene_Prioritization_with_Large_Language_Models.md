# # 基于大型语言模型的基因优先级排序：调查与改进策略

发布时间：2025年01月30日

`Agent

理由：这篇论文主要讨论了使用多代理技术和大型语言模型（LLMs）来改进罕见遗传疾病的诊断流程。多代理技术在这里起到了关键作用，通过将任务分解为更小的子集，并结合人类表型本体论（HPO）分类，显著提升了致病基因识别的准确性。因此，这篇论文的核心内容与“Agent”分类相关，因为它涉及多代理系统的应用和优化。` `罕见疾病`

> Survey and Improvement Strategies for Gene Prioritization with Large Language Models

# 摘要

> 罕见疾病因患者数据稀缺和遗传多样性而难以诊断。尽管变异优先级排序技术有所进步，许多病例仍无法确诊。虽然大型语言模型（LLMs）在医学考试中表现出色，但其在罕见遗传疾病诊断中的效果尚未得到验证。为识别致病基因，我们对多种LLMs进行了基因优先级排序的基准测试。通过多代理和人类表型本体论（HPO）分类，我们根据表型和可解决程度对患者进行分类。随着基因集规模增大，LLM性能下降，因此我们采用分而治之策略，将任务分解为更小的子集。在基线测试中，GPT-4表现最佳，正确排序致病基因的准确率接近30%。多代理和HPO方法有效区分了易解决和难解决的病例，凸显了已知基因-表型关联和表型特异性的重要性。我们发现，具有特定表型或明确关联的病例更容易准确诊断。然而，LLMs对研究充分的基因存在偏见，且对输入顺序敏感，这影响了基因优先级排序。通过分而治之策略，我们克服了这些偏见，提高了准确性。结合HPO分类、多代理技术和LLM策略，我们显著提升了致病基因识别的准确性。这一方法不仅简化了罕见疾病的诊断流程，还促进了对未解决病例的重新分析，加速了基因发现，为靶向诊断和治疗的发展提供了支持。

> Rare diseases are challenging to diagnose due to limited patient data and genetic diversity. Despite advances in variant prioritization, many cases remain undiagnosed. While large language models (LLMs) have performed well in medical exams, their effectiveness in diagnosing rare genetic diseases has not been assessed. To identify causal genes, we benchmarked various LLMs for gene prioritization. Using multi-agent and Human Phenotype Ontology (HPO) classification, we categorized patients based on phenotypes and solvability levels. As gene set size increased, LLM performance deteriorated, so we used a divide-and-conquer strategy to break the task into smaller subsets. At baseline, GPT-4 outperformed other LLMs, achieving near 30% accuracy in ranking causal genes correctly. The multi-agent and HPO approaches helped distinguish confidently solved cases from challenging ones, highlighting the importance of known gene-phenotype associations and phenotype specificity. We found that cases with specific phenotypes or clear associations were more accurately solved. However, we observed biases toward well-studied genes and input order sensitivity, which hindered gene prioritization. Our divide-and-conquer strategy improved accuracy by overcoming these biases. By utilizing HPO classification, novel multi-agent techniques, and our LLM strategy, we improved causal gene identification accuracy compared to our baseline evaluation. This approach streamlines rare disease diagnosis, facilitates reanalysis of unsolved cases, and accelerates gene discovery, supporting the development of targeted diagnostics and therapies.

[Arxiv](https://arxiv.org/abs/2501.18794)