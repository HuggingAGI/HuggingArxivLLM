# <翻译失败>

发布时间：2025年08月27日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> MODE: Mixture of Document Experts for RAG

# 摘要

> <翻译失败>

> Retrieval-Augmented Generation (RAG) often relies on large vector databases and cross-encoders tuned for large-scale corpora, which can be excessive for small, domain-specific collections. We present MODE (Mixture of Document Experts), a lightweight alternative that replaces fine-grained nearest-neighbor search with cluster-and-route retrieval. Documents are embedded, grouped into semantically coherent clusters, and represented by cached centroids. At query time, we route to the top centroid(s) and retrieve context only within those clusters, eliminating external vector-database infrastructure and reranking while keeping latency low. On HotpotQA and SQuAD corpora with 100-500 chunks, MODE matches or exceeds a dense-retrieval baseline in answer quality while reducing end-to-end retrieval time. Ablations show that cluster granularity and multi-cluster routing control the recall/precision trade-off, and that tighter clusters improve downstream accuracy. MODE offers a practical recipe for small and medium corpora where simplicity, speed, and topical focus matter.

[Arxiv](https://arxiv.org/abs/2509.00100)