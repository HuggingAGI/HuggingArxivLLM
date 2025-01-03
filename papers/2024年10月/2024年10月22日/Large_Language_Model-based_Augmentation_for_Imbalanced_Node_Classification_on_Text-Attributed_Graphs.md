# 基于大语言模型的增强方法在文本属性图上的不平衡节点分类中的应用

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文探讨了如何利用大型语言模型（LLMs）的文本生成能力来解决文本属性图（TAGs）中的节点不平衡问题。具体来说，作者提出了一种名为LA-TAG的方法，通过生成合成文本并引入基于文本的链接预测器来增强图数据。这种方法直接应用了LLMs的能力来解决实际问题，属于LLM在具体应用场景中的使用，因此分类为“LLM应用”。` `图数据` `文本分析`

> Large Language Model-based Augmentation for Imbalanced Node Classification on Text-Attributed Graphs

# 摘要

> # 摘要
图节点分类常受类别不平衡困扰，导致性能偏差和实际应用中的高风险。尽管已有多种数据解决方案，但均未聚焦于文本属性图（TAGs），忽视了利用文本特征中的丰富语义提升少数节点分类的潜力。为此，我们探索了在文本空间中增强图数据的可能性，借助大型语言模型（LLMs）的文本生成能力，解决TAGs上的节点不平衡问题。我们提出了一种名为LA-TAG的新方法，通过LLMs生成基于现有节点文本的合成文本，并引入基于文本的链接预测器，将合成节点与现有节点连接。实验表明，LA-TAG在多个数据集和评估指标上均显著优于传统非文本数据增强策略和特定节点不平衡解决方案，展现了LLMs在解决TAGs不平衡问题上的巨大潜力。

> Node classification on graphs frequently encounters the challenge of class imbalance, leading to biased performance and posing significant risks in real-world applications. Although several data-centric solutions have been proposed, none of them focus on Text-Attributed Graphs (TAGs), and therefore overlook the potential of leveraging the rich semantics encoded in textual features for boosting the classification of minority nodes. Given this crucial gap, we investigate the possibility of augmenting graph data in the text space, leveraging the textual generation power of Large Language Models (LLMs) to handle imbalanced node classification on TAGs. Specifically, we propose a novel approach called LA-TAG (LLM-based Augmentation on Text-Attributed Graphs), which prompts LLMs to generate synthetic texts based on existing node texts in the graph. Furthermore, to integrate these synthetic text-attributed nodes into the graph, we introduce a text-based link predictor to connect the synthesized nodes with the existing nodes. Our experiments across multiple datasets and evaluation metrics show that our framework significantly outperforms traditional non-textual-based data augmentation strategies and specific node imbalance solutions. This highlights the promise of using LLMs to resolve imbalance issues on TAGs.

[Arxiv](https://arxiv.org/abs/2410.16882)