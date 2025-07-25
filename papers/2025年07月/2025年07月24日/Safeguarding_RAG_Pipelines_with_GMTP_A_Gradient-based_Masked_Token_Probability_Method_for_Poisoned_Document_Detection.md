# # 守护 RAG 管道：基于梯度的遮蔽标记概率方法（GMTP）用于识别中毒文档

发布时间：2025年07月24日

`RAG` `人工智能安全`

> Safeguarding RAG Pipelines with GMTP: A Gradient-based Masked Token Probability Method for Poisoned Document Detection

# 摘要

> 检索增强生成（RAG）通过提供外部知识，显著提升了大型语言模型的准确性和时效性。然而，这种依赖外部知识的方式也带来了安全隐患：攻击者可能将有毒文档注入知识库，从而操控生成结果，使其产生有害或误导性的输出。针对这一问题，我们提出了一种全新的防御方法——基于梯度的遮蔽令牌概率（GMTP），用于识别并过滤恶意编造的文档。具体来说，GMTP通过分析检索器相似度函数的梯度，识别出对生成结果影响较大的关键令牌。随后，这些关键令牌被遮蔽，并通过遮蔽语言模型（MLM）检查其概率。由于注入的恶意令牌通常具有显著较低的遮蔽令牌概率，GMTP能够轻松识别并过滤这些恶意文档，实现高精度的防护。实验结果表明，GMTP在消除超过90%有毒内容的同时，保留了相关文档，从而在多种数据集和对抗场景下，保持了稳健的检索和生成性能。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by providing external knowledge for accurate and up-to-date responses. However, this reliance on external sources exposes a security risk, attackers can inject poisoned documents into the knowledge base to steer the generation process toward harmful or misleading outputs. In this paper, we propose Gradient-based Masked Token Probability (GMTP), a novel defense method to detect and filter out adversarially crafted documents. Specifically, GMTP identifies high-impact tokens by examining gradients of the retriever's similarity function. These key tokens are then masked, and their probabilities are checked via a Masked Language Model (MLM). Since injected tokens typically exhibit markedly low masked-token probabilities, this enables GMTP to easily detect malicious documents and achieve high-precision filtering. Experiments demonstrate that GMTP is able to eliminate over 90% of poisoned content while retaining relevant documents, thus maintaining robust retrieval and generation performance across diverse datasets and adversarial settings.

[Arxiv](https://arxiv.org/abs/2507.18202)