# VERIRAG：通过检索增强生成中的统计审核实现医疗索赔验证

发布时间：2025年07月23日

`RAG` `临床决策支持`

> VERIRAG: Healthcare Claim Verification via Statistical Audit in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统在临床决策支持领域被广泛应用，但它们存在一个关键缺陷：能够检索证据，却无法评估证据的科学质量。例如，一篇声称“抗氧化蛋白在接受alloferon治疗后减少”的论文与一项严格多实验室重复研究会被视为同等可信，即使前者缺乏科学严谨性，甚至已被撤回。为解决这一问题，我们提出了VERIRAG框架，该框架在三个关键方面做出了创新：(i) Veritable，一个包含11个要点的清单，用于评估每个来源的方法严谨性，包括数据完整性和统计有效性；(ii) 难以变动（HV）分数，一个定量聚合器，根据证据的质量和多样性对其进行加权；(iii) 动态接受阈值，根据主张的非凡程度调整所需证据的标准。在四个数据集——包括撤回、冲突、全面和已定论的科学语料库——VERIRAG方法始终优于所有基线，实现了绝对F1分数从0.53到0.65的提升，与各数据集中的次优方法相比，每项数据集的改进幅度达到10到14个百分点。我们将发布所有用于再现我们结果的材料。


> Retrieval-augmented generation (RAG) systems are increasingly adopted in clinical decision support, yet they remain methodologically blind-they retrieve evidence but cannot vet its scientific quality. A paper claiming "Antioxidant proteins decreased after alloferon treatment" and a rigorous multi-laboratory replication study will be treated as equally credible, even if the former lacked scientific rigor or was even retracted. To address this challenge, we introduce VERIRAG, a framework that makes three notable contributions: (i) the Veritable, an 11-point checklist that evaluates each source for methodological rigor, including data integrity and statistical validity; (ii) a Hard-to-Vary (HV) Score, a quantitative aggregator that weights evidence by its quality and diversity; and (iii) a Dynamic Acceptance Threshold, which calibrates the required evidence based on how extraordinary a claim is. Across four datasets-comprising retracted, conflicting, comprehensive, and settled science corpora-the VERIRAG approach consistently outperforms all baselines, achieving absolute F1 scores ranging from 0.53 to 0.65, representing a 10 to 14 point improvement over the next-best method in each respective dataset. We will release all materials necessary for reproducing our results.

[Arxiv](https://arxiv.org/abs/2507.17948)