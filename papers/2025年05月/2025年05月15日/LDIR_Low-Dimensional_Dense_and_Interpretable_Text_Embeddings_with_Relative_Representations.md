# LDIR：低维稠密且可解释的文本嵌入，结合相对表示

发布时间：2025年05月15日

`LLM应用` `信息检索`

> LDIR: Low-Dimensional Dense and Interpretable Text Embeddings with Relative Representations

# 摘要

> 语义文本表示是自然语言处理领域的基础任务。现有的文本嵌入方法（如SimCSE和LLM2Vec）表现出色，但其维度值难以解释。经典的词袋模型虽然可解释，但性能不佳。最近，Benara等人（2024）提出了一种基于大型语言模型的可解释文本嵌入方法，通过回答问题生成“0/1”嵌入。这些嵌入通常是高维的（超过10,000维）。在本研究中，我们提出了低维（低于500维）的密集且可解释的文本嵌入方法——相对表示（LDIR）。其各维度的数值通过最远点采样方法，反映了与不同锚文本的语义相关性，既实现了语义表示，又具备一定的可追踪性和可解释性。我们在多个语义文本相似度、检索和聚类任务上验证了LDIR。实验结果表明，LDIR的表现接近黑箱基线模型，且在维度数量远低于可解释嵌入基线的情况下，性能更优。代码可从https://github.com/szu-tera/LDIR获取。

> Semantic text representation is a fundamental task in the field of natural language processing. Existing text embedding (e.g., SimCSE and LLM2Vec) have demonstrated excellent performance, but the values of each dimension are difficult to trace and interpret. Bag-of-words, as classic sparse interpretable embeddings, suffers from poor performance. Recently, Benara et al. (2024) propose interpretable text embeddings using large language models, which forms "0/1" embeddings based on responses to a series of questions. These interpretable text embeddings are typically high-dimensional (larger than 10,000). In this work, we propose Low-dimensional (lower than 500) Dense and Interpretable text embeddings with Relative representations (LDIR). The numerical values of its dimensions indicate semantic relatedness to different anchor texts through farthest point sampling, offering both semantic representation as well as a certain level of traceability and interpretability. We validate LDIR on multiple semantic textual similarity, retrieval, and clustering tasks. Extensive experimental results show that LDIR performs close to the black-box baseline models and outperforms the interpretable embeddings baselines with much fewer dimensions. Code is available at https://github.com/szu-tera/LDIR.

[Arxiv](https://arxiv.org/abs/2505.10354)