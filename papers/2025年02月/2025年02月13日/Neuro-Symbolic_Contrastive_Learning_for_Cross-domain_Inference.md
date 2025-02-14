# 跨域推理的神经符号对比学习方法

发布时间：2025年02月13日

`LLM理论` `自然语言推理` `神经符号方法`

> Neuro-Symbolic Contrastive Learning for Cross-domain Inference

# 摘要

> 预训练语言模型（PLMs）在自然语言推理（NLI）任务中表现突出，但其对文本扰动的敏感性和对大规模数据的依赖，显示出过度依赖浅层启发式方法的局限。相比之下，归纳逻辑编程（ILP）擅长从多样、稀疏且有限的数据中推断逻辑关系，但其离散性质对输入的精确性要求限制了实际应用。本文提出了一种创新的结合方法：神经符号对比学习，旨在通过平滑且可微的优化，在逻辑函数的离散、噪声和稀疏空间中提升逻辑准确性。我们发现，通过将数据表示为逻辑程序和规则集，可以在神经符号框架中有效嵌入抽象逻辑关系。这种嵌入方式不仅能够捕捉具有相似语义逻辑关系的多样化文本信息，还能区分具有不同逻辑关系的相似文本关系。实验结果表明，我们的方法显著提升了模型在推理任务中的泛化和推理能力。

> Pre-trained language models (PLMs) have made significant advances in natural language inference (NLI) tasks, however their sensitivity to textual perturbations and dependence on large datasets indicate an over-reliance on shallow heuristics. In contrast, inductive logic programming (ILP) excels at inferring logical relationships across diverse, sparse and limited datasets, but its discrete nature requires the inputs to be precisely specified, which limits their application. This paper proposes a bridge between the two approaches: neuro-symbolic contrastive learning. This allows for smooth and differentiable optimisation that improves logical accuracy across an otherwise discrete, noisy, and sparse topological space of logical functions.  We show that abstract logical relationships can be effectively embedded within a neuro-symbolic paradigm, by representing data as logic programs and sets of logic rules. The embedding space captures highly varied textual information with similar semantic logical relations, but can also separate similar textual relations that have dissimilar logical relations. Experimental results demonstrate that our approach significantly improves the inference capabilities of the models in terms of generalisation and reasoning.

[Arxiv](https://arxiv.org/abs/2502.09213)