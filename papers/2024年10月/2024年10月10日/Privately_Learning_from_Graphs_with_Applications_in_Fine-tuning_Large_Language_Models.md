# 基于图数据的隐私学习及其在LLM微调中的应用

发布时间：2024年10月10日

`LLM应用

理由：这篇论文主要讨论了在敏感图数据上对大型语言模型（LLMs）进行微调，并提出了一种隐私保护的关系学习管道。虽然涉及隐私保护和关系学习，但其核心应用场景是LLMs在特定数据（图数据）上的微调和应用，因此应归类为LLM应用。`

> Privately Learning from Graphs with Applications in Fine-tuning Large Language Models

# 摘要

> # 摘要
图数据为实体间的关系和交互提供了独特的视角，补充了文本、图像和视频等数据模态。通过整合图数据中的关系信息，AI模型能够超越传统任务，扩展其能力。然而，金融和医疗等敏感领域的关系数据往往包含私人信息，隐私保护至关重要。现有的隐私保护方法，如DP-SGD，依赖于梯度解耦假设，但由于耦合训练样本间的固有依赖性，这些方法并不适合关系学习。为此，我们提出了一种隐私保护的关系学习管道，在训练过程中解耦采样关系中的依赖关系，并通过定制化的DP-SGD应用确保差分隐私。我们将此方法应用于敏感图数据上的大型语言模型（LLMs）微调，并解决了相关的计算复杂性。我们在四种文本属性图上的真实关系数据上评估了该方法，使用了不同规模的LLMs（如BERT、Llama2）。结果表明，在关系学习任务中取得了显著改进，同时在训练过程中保持了强大的隐私保证。此外，我们还探讨了隐私、效用和计算效率之间的权衡，为实际部署提供了见解。代码可在https://github.com/Graph-COM/PvGaLM获取。

> Graphs offer unique insights into relationships and interactions between entities, complementing data modalities like text, images, and videos. By incorporating relational information from graph data, AI models can extend their capabilities beyond traditional tasks. However, relational data in sensitive domains such as finance and healthcare often contain private information, making privacy preservation crucial. Existing privacy-preserving methods, such as DP-SGD, which rely on gradient decoupling assumptions, are not well-suited for relational learning due to the inherent dependencies between coupled training samples. To address this challenge, we propose a privacy-preserving relational learning pipeline that decouples dependencies in sampled relations during training, ensuring differential privacy through a tailored application of DP-SGD. We apply this method to fine-tune large language models (LLMs) on sensitive graph data, and tackle the associated computational complexities. Our approach is evaluated on LLMs of varying sizes (e.g., BERT, Llama2) using real-world relational data from four text-attributed graphs. The results demonstrate significant improvements in relational learning tasks, all while maintaining robust privacy guarantees during training. Additionally, we explore the trade-offs between privacy, utility, and computational efficiency, offering insights into the practical deployment of our approach. Code is available at https://github.com/Graph-COM/PvGaLM.

[Arxiv](https://arxiv.org/abs/2410.08299)