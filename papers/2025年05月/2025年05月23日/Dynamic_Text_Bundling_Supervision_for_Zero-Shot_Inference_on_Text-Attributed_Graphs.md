# 动态文本捆绑监督：文本属性图的零样本推理新方案

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在文本属性图（TAGs）中的应用，提出了动态文本打包监督（DENSE）方法来解决LLMs在图结构数据中的应用问题。该研究属于LLMs的实际应用探索，因此归类为LLM应用。` `图神经网络` `文本属性图`

> Dynamic Text Bundling Supervision for Zero-Shot Inference on Text-Attributed Graphs

# 摘要

> 大型语言模型（LLMs）凭借其卓越的泛化能力，在零样本学习领域大放异彩。近期，LLMs在文本属性图（TAGs）中的应用引发了广泛关注。然而，LLMs的实际应用面临两大挑战：图结构信息有限和响应结果不可靠。由于难以处理与图拓扑结构相隔离的文本属性，LLMs的表现受到限制。更棘手的是，信息不充分和LLMs自身固有的弱点（如幻觉现象）会导致预测结果的可靠性下降。

针对上述问题，我们提出了一种名为动态文本打包监督（DENSE）的创新方法。该方法通过向LLMs提交文本打包查询获取打包级别的标签，并利用这些标签监督图神经网络的训练过程。具体而言，我们首先采样一组文本包，每个包包含一组具有相近文本内容的节点及其对应文本。随后，向LLMs提交这些打包文本以获取标签。这些打包标签不仅用于监督图神经网络的优化，还用于进一步精炼文本包以剔除噪声项。

为了证明我们的设计思路，我们提供了对所提方法的理论分析。通过在十个数据集上的广泛实验，验证了DENSE方法的有效性。这一方法为LLMs在图结构数据中的应用开辟了新的研究方向。

> Large language models (LLMs) have been used in many zero-shot learning problems, with their strong generalization ability. Recently, adopting LLMs in text-attributed graphs (TAGs) has drawn increasing attention. However, the adoption of LLMs faces two major challenges: limited information on graph structure and unreliable responses. LLMs struggle with text attributes isolated from the graph topology. Worse still, they yield unreliable predictions due to both information insufficiency and the inherent weakness of LLMs (e.g., hallucination). Towards this end, this paper proposes a novel method named Dynamic Text Bundling Supervision (DENSE) that queries LLMs with bundles of texts to obtain bundle-level labels and uses these labels to supervise graph neural networks. Specifically, we sample a set of bundles, each containing a set of nodes with corresponding texts of close proximity. We then query LLMs with the bundled texts to obtain the label of each bundle. Subsequently, the bundle labels are used to supervise the optimization of graph neural networks, and the bundles are further refined to exclude noisy items. To justify our design, we also provide theoretical analysis of the proposed method. Extensive experiments across ten datasets validate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2505.17599)