# 增强型语义检索对比学习在序列推荐中的应用

发布时间：2025年03月06日

`LLM应用` `电子商务` `在线平台`

> Semantic Retrieval Augmented Contrastive Learning for Sequential Recommendation

# 摘要

> 序列推荐通过分析用户的历史行为序列建模其偏好，这对各类在线平台至关重要。然而，数据稀疏性仍是该领域的主要挑战，因大多数用户互动有限，众多项目关注度较低。为缓解这一问题，对比学习被广泛应用。通过从数据中构建正样本对，并最大化其在嵌入空间中的一致性，对比学习能更高效地利用现有数据。然而，构建合理的正样本对是对比学习成功的关键，现有方法却面临两大挑战：要么依赖稀疏协作信号中学得的表示，要么采用引入显著不确定性的随机扰动。为解决这些限制，我们提出了一种名为语义检索增强对比学习（SRA-CL）的新方法，通过引入语义信息提升对比样本的可靠性。SRA-CL包含两大核心组件：（1）跨序列对比学习，通过用户语义检索，利用大型语言模型（LLMs）理解多样化的用户偏好，检索语义相似的用户，并通过可学习的样本合成方法形成可靠的正样本；（2）序列内对比学习，通过项目语义检索，利用LLMs理解项目并检索相似项目，执行基于语义的项目替换，为对比学习创建语义一致的增强视图。SRA-CL设计灵活，可轻松集成到标准的序列推荐模型中。在四个公共数据集上的广泛实验结果证实了该方法的有效性和通用性。

> Sequential recommendation aims to model user preferences based on historical behavior sequences, which is crucial for various online platforms. Data sparsity remains a significant challenge in this area as most users have limited interactions and many items receive little attention. To mitigate this issue, contrastive learning has been widely adopted. By constructing positive sample pairs from the data itself and maximizing their agreement in the embedding space,it can leverage available data more effectively. Constructing reasonable positive sample pairs is crucial for the success of contrastive learning. However, current approaches struggle to generate reliable positive pairs as they either rely on representations learned from inherently sparse collaborative signals or use random perturbations which introduce significant uncertainty. To address these limitations, we propose a novel approach named Semantic Retrieval Augmented Contrastive Learning (SRA-CL), which leverages semantic information to improve the reliability of contrastive samples. SRA-CL comprises two main components: (1) Cross-Sequence Contrastive Learning via User Semantic Retrieval, which utilizes large language models (LLMs) to understand diverse user preferences and retrieve semantically similar users to form reliable positive samples through a learnable sample synthesis method; and (2) Intra-Sequence Contrastive Learning via Item Semantic Retrieval, which employs LLMs to comprehend items and retrieve similar items to perform semantic-based item substitution, thereby creating semantically consistent augmented views for contrastive learning. SRA-CL is plug-and-play and can be integrated into standard sequential recommendation models. Extensive experiments on four public datasets demonstrate the effectiveness and generalizability of the proposed approach.

[Arxiv](https://arxiv.org/abs/2503.04162)