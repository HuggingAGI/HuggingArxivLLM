# # 基于图的法律案例检索可重复性研究

发布时间：2025年04月11日

`LLM应用

理由：这篇论文讨论了法律检索中的应用，特别是利用大型语言模型（LLM）来提升检索方法的性能和可重复性。它主要关注于将语言模型应用于特定领域（法律检索），属于LLM应用类别。` `法律检索` `法律信息检索`

> A Reproducibility Study of Graph-Based Legal Case Retrieval

# 摘要

> 法律检索是信息检索（IR）领域的热门研究方向，其核心任务是根据查询案例检索相关案例，通常通过语言模型作为编码器来建模案例相似性。近期，Tang等人提出了CaseLink，这是一种基于图的法律案例检索新方法，将案件和法律指控建模为网络节点，边则表示引用和共享语义等关系。该方法通过捕捉超越独立文档层面的高阶关系，为法律检索提供了新视角。然而，尽管这种方法在基于图的法律IR这一新兴领域具有潜力，但近期研究指出在再现新颖结果方面面临挑战，多个研究都报告了再现先前发现的困难。因此，本研究对CaseLink进行了再现，旨在支持该领域的未来研究。具体而言，我们通过（i）再现原始研究设置，并（ii）将其应用于额外数据集来评估其可靠性和泛化能力。在此基础上，我们（iii）评估了更复杂图数据表示的性能，并（iv）引入开源大型语言模型（LLM）以解决闭源模型的局限性。我们的研究旨在增进对基于图方法在法律IR中的理解，并为提高该领域的可重复性做出贡献。为此，我们向社区开放了所有实现和实验成果。

> Legal retrieval is a widely studied area in Information Retrieval (IR) and a key task in this domain is retrieving relevant cases based on a given query case, often done by applying language models as encoders to model case similarity. Recently, Tang et al. proposed CaseLink, a novel graph-based method for legal case retrieval, which models both cases and legal charges as nodes in a network, with edges representing relationships such as references and shared semantics. This approach offers a new perspective on the task by capturing higher-order relationships of cases going beyond the stand-alone level of documents. However, while this shift in approaching legal case retrieval is a promising direction in an understudied area of graph-based legal IR, challenges in reproducing novel results have recently been highlighted, with multiple studies reporting difficulties in reproducing previous findings. Thus, in this work we reproduce CaseLink, a graph-based legal case retrieval method, to support future research in this area of IR. In particular, we aim to assess its reliability and generalizability by (i) first reproducing the original study setup and (ii) applying the approach to an additional dataset. We then build upon the original implementations by (iii) evaluating the approach's performance when using a more sophisticated graph data representation and (iv) using an open large language model (LLM) in the pipeline to address limitations that are known to result from using closed models accessed via an API. Our findings aim to improve the understanding of graph-based approaches in legal IR and contribute to improving reproducibility in the field. To achieve this, we share all our implementations and experimental artifacts with the community.

[Arxiv](https://arxiv.org/abs/2504.08400)