# 语义体积：量化与检测大型语言模型中的内外部不确定性

发布时间：2025年02月28日

`LLM理论` `人工智能` `机器学习`

> Semantic Volume: Quantifying and Detecting both External and Internal Uncertainty in LLMs

# 摘要

> 大型语言模型（LLMs）通过编码大量事实知识，在多样化任务中展现了卓越的表现。然而，它们仍然容易产生幻觉，生成错误或误导性信息，通常伴随着高度的不确定性。现有的幻觉检测方法主要集中在量化模型内部的不确定性，这种不确定性源于模型内部缺失或冲突的知识。然而，幻觉也可能源于外部不确定性，即模糊的用户查询导致多种可能的解释。

在本研究中，我们引入了Semantic Volume，这是一种全新的数学度量方法，用于量化LLMs中的外部和内部不确定性。我们的方法通过扰动查询和响应，将它们嵌入到语义空间中，并计算嵌入向量的Gram矩阵的行列式，从而捕获它们的分散程度作为不确定性的一种度量。我们的框架提供了一种通用且无需监督的不确定性检测方法，无需访问LLMs的白盒。

我们在外部和内部不确定性检测方面进行了广泛的实验，结果表明，我们的Semantic Volume方法在两项任务中均一致优于现有基线。此外，我们提供了理论见解，将我们的度量与微分熵联系起来，统一并扩展了之前基于采样的不确定性度量，如语义熵。Semantic Volume被证明是一种稳健且可解释的方法，通过系统地检测用户查询和模型响应中的不确定性，从而提高LLMs的可靠性。

> Large language models (LLMs) have demonstrated remarkable performance across diverse tasks by encoding vast amounts of factual knowledge. However, they are still prone to hallucinations, generating incorrect or misleading information, often accompanied by high uncertainty. Existing methods for hallucination detection primarily focus on quantifying internal uncertainty, which arises from missing or conflicting knowledge within the model. However, hallucinations can also stem from external uncertainty, where ambiguous user queries lead to multiple possible interpretations. In this work, we introduce Semantic Volume, a novel mathematical measure for quantifying both external and internal uncertainty in LLMs. Our approach perturbs queries and responses, embeds them in a semantic space, and computes the determinant of the Gram matrix of the embedding vectors, capturing their dispersion as a measure of uncertainty. Our framework provides a generalizable and unsupervised uncertainty detection method without requiring white-box access to LLMs. We conduct extensive experiments on both external and internal uncertainty detection, demonstrating that our Semantic Volume method consistently outperforms existing baselines in both tasks. Additionally, we provide theoretical insights linking our measure to differential entropy, unifying and extending previous sampling-based uncertainty measures such as the semantic entropy. Semantic Volume is shown to be a robust and interpretable approach to improving the reliability of LLMs by systematically detecting uncertainty in both user queries and model responses.

[Arxiv](https://arxiv.org/abs/2502.21239)