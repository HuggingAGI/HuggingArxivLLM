# 基于LLMs的少样本图分布外检测方法

发布时间：2025年03月27日

`LLM应用` `图计算`

> Few-Shot Graph Out-of-Distribution Detection with LLMs

# 摘要

> 现有的图结构出分布（OOD）检测方法通常依赖于大量标记的在分布（ID）数据来训练图神经网络（GNN）分类器。然而，在文本属性图（TAGs）中获取高质量标记节点具有挑战性且成本高昂，这源于其复杂的文本和结构特性。大型语言模型（LLMs）以其在文本任务中的强大零样本能力而闻名，展现出潜力，但它们难以自然捕获TAGs中固有的关键结构信息，从而限制了其直接有效性。

为了解决这些挑战，我们提出了一种通用框架LLM-GOOD，该框架有效结合了LLMs和GNNs的优势，以提高图OOD检测的数据效率。具体而言，我们首先利用LLMs强大的零样本能力筛选出可能的OOD节点，从而大幅降低人工标注负担。为了最小化LLM的使用和成本，我们仅将其用于标注一小部分未标记节点。随后，我们使用这些噪声标签训练一个轻量级GNN过滤器，通过结合文本和结构信息，实现对其他所有未标记节点ID状态的高效预测。从GNN过滤器中获得节点嵌入后，我们可以应用基于信息量的方法，选择最 valuable 的节点进行精确人工标注。最后，我们利用这些准确标注的ID节点训练目标ID分类器。在四个真实世界TAG数据集上的广泛实验表明，LLM-GOOD显著降低了人工标注成本，并在ID分类准确性和OOD检测性能方面均优于现有最先进基线。


> Existing methods for graph out-of-distribution (OOD) detection typically depend on training graph neural network (GNN) classifiers using a substantial amount of labeled in-distribution (ID) data. However, acquiring high-quality labeled nodes in text-attributed graphs (TAGs) is challenging and costly due to their complex textual and structural characteristics. Large language models (LLMs), known for their powerful zero-shot capabilities in textual tasks, show promise but struggle to naturally capture the critical structural information inherent to TAGs, limiting their direct effectiveness.
  To address these challenges, we propose LLM-GOOD, a general framework that effectively combines the strengths of LLMs and GNNs to enhance data efficiency in graph OOD detection. Specifically, we first leverage LLMs' strong zero-shot capabilities to filter out likely OOD nodes, significantly reducing the human annotation burden. To minimize the usage and cost of the LLM, we employ it only to annotate a small subset of unlabeled nodes. We then train a lightweight GNN filter using these noisy labels, enabling efficient predictions of ID status for all other unlabeled nodes by leveraging both textual and structural information. After obtaining node embeddings from the GNN filter, we can apply informativeness-based methods to select the most valuable nodes for precise human annotation. Finally, we train the target ID classifier using these accurately annotated ID nodes. Extensive experiments on four real-world TAG datasets demonstrate that LLM-GOOD significantly reduces human annotation costs and outperforms state-of-the-art baselines in terms of both ID classification accuracy and OOD detection performance.

[Arxiv](https://arxiv.org/abs/2503.22097)