# Chameleon：应用于语言模型预训练与微调的灵活数据混合框架

发布时间：2025年05月30日

`LLM理论` `机器学习`

> Chameleon: A Flexible Data-mixing Framework for Language Model Pretraining and Finetuning

# 摘要

> 训练数据的混合方式对大型语言模型的泛化性能有着重大影响。现有的领域重新加权方法通常依赖于昂贵的权重计算，并且在引入新数据时需要重新训练模型。针对这一问题，我们提出了一种灵活高效的数据混合框架——Chameleon，它通过杠杆分数量化在学习到的嵌入空间中各领域的相对重要性。首先，我们在领域嵌入上构建一个领域亲和力矩阵。由此产生的杠杆分数决定了一个混合比例，使得共享相似嵌入表示的领域在混合中占据更高的权重。这种形式化表达使得我们可以直接通过计算新领域的嵌入表示来迁移至新数据。在实验中，我们展示了Chameleon在三个关键场景下的优势：(i) 我们计算的权重在预训练领域上提升了性能，且计算量仅为现有方法的零头；(ii) Chameleon无需代理重新训练即可适应数据变化，当应用于新数据时，显著提升了少样本推理的准确性；(iii) 我们的方法在微调过程中实现了高效的领域重新加权，在所有微调领域上一致地降低了测试困惑度。我们的代码可在GitHub上获取：https://github.com/LIONS-EPFL/Chameleon.

> Training data mixtures greatly impact the generalization performance of large language models. Existing domain reweighting methods often rely on costly weight computations and require retraining when new data is introduced. To this end, we introduce a flexible and efficient data mixing framework, Chameleon, that employs leverage scores to quantify domain importance within a learned embedding space. We first construct a domain affinity matrix over domain embeddings. The induced leverage scores determine a mixture that upweights domains sharing common representations in embedding space. This formulation allows direct transfer to new data by computing the new domain embeddings. In experiments, we demonstrate improvements over three key scenarios: (i) our computed weights improve performance on pretraining domains with a fraction of the compute of existing methods; (ii) Chameleon can adapt to data changes without proxy retraining, boosting few-shot reasoning accuracies when transferred to new data; (iii) our method enables efficient domain reweighting in finetuning, consistently improving test perplexity on all finetuning domains over uniform mixture. Our code is available at https://github.com/LIONS-EPFL/Chameleon.

[Arxiv](https://arxiv.org/abs/2505.24844)