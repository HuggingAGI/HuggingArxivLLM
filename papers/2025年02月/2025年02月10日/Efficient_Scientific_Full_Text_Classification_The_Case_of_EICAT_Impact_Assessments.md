# 高效科学全文分类方法：以EICAT影响评估为例

发布时间：2025年02月10日

`LLM应用`

> Efficient Scientific Full Text Classification: The Case of EICAT Impact Assessments

# 摘要

> 本研究探索了利用小型BERT模型和本地大语言模型（如Llama-3.1 8B）高效分类科学全文的策略，重点研究如何通过选择输入句子的子集，在减少输入规模的同时提升分类性能。为此，我们构建了一个全新的数据集，包含入侵生物学领域关注入侵物种影响的全文科学论文，这些论文与国际自然保护联盟（IUCN）公开的影响评估相匹配。通过大量实验，我们发现，无论是人类标注、LLM生成的标注，还是可解释性得分，都可以用于训练句子选择模型，从而在优化输入长度的同时，提升编码器和解码器语言模型的性能。即使与能够处理完整文本输入的ModernBERT等模型相比，我们的方法也能取得更好的效果。此外，我们发现，通过增加一点成本，重复采样更短的输入被证明是一种非常有效的策略，能够进一步提升分类性能。

> This study explores strategies for efficiently classifying scientific full texts using both small, BERT-based models and local large language models like Llama-3.1 8B. We focus on developing methods for selecting subsets of input sentences to reduce input size while simultaneously enhancing classification performance. To this end, we compile a novel dataset consisting of full-text scientific papers from the field of invasion biology, specifically addressing the impacts of invasive species. These papers are aligned with publicly available impact assessments created by researchers for the International Union for Conservation of Nature (IUCN). Through extensive experimentation, we demonstrate that various sources like human evidence annotations, LLM-generated annotations or explainability scores can be used to train sentence selection models that improve the performance of both encoder- and decoder-based language models while optimizing efficiency through the reduction in input length, leading to improved results even if compared to models like ModernBERT that are able to handle the complete text as input. Additionally, we find that repeated sampling of shorter inputs proves to be a very effective strategy that, at a slightly increased cost, can further improve classification performance.

[Arxiv](https://arxiv.org/abs/2502.06551)