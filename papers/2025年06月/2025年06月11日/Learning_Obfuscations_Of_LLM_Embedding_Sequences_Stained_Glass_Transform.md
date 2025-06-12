# 探索LLM嵌入序列的混淆：彩窗变换法

发布时间：2025年06月11日

`LLM理论` `数据隐私`

> Learning Obfuscations Of LLM Embedding Sequences: Stained Glass Transform

# 摘要

> AI计算基础设施的高昂成本以及大型语言模型（LLMs）的稳健服务挑战，推动了托管模型即服务（Model-as-a-service）的广泛应用。即使企业选择内部部署，计算资源也通常被多个团队共享以提高投资回报率。无论是哪种部署方式，模型仅处理明文数据，这意味着企业数据所有者必须允许其数据以明文形式出现在共享或多租户的计算环境中。这使得拥有私人或敏感数据的企业在使用这些部署时往往犹豫不决或受限。本研究中，我们引入了“彩绘玻璃变换”（Stained Glass Transform），这是一种基于学习的、随机的、依赖序列的LLM词嵌入变换，能够在信息论层面保护LLM输入隐私，同时保持模型的效用。我们从理论上将一类特定的彩绘玻璃变换与高斯混合模型的互信息理论建立了联系。随后，我们基于互信息计算后验隐私估计，并通过分词级别的隐私指标和标准的LLM性能基准测试，验证了变换后嵌入实例的隐私保护效果和模型效用。

> The high cost of ownership of AI compute infrastructure and challenges of robust serving of large language models (LLMs) has led to a surge in managed Model-as-a-service deployments. Even when enterprises choose on-premises deployments, the compute infrastructure is typically shared across many teams in order to maximize the return on investment. In both scenarios the deployed models operate only on plaintext data, and so enterprise data owners must allow their data to appear in plaintext on a shared or multi-tenant compute infrastructure. This results in data owners with private or sensitive data being hesitant or restricted in what data they use with these types of deployments. In this work we introduce the Stained Glass Transform, a learned, stochastic, and sequence dependent transformation of the word embeddings of an LLM which information theoretically provides privacy to the input of the LLM while preserving the utility of model. We theoretically connect a particular class of Stained Glass Transforms to the theory of mutual information of Gaussian Mixture Models. We then calculate a-postiori privacy estimates, based on mutual information, and verify the privacy and utility of instances of transformed embeddings through token level metrics of privacy and standard LLM performance benchmarks.

[Arxiv](https://arxiv.org/abs/2506.09452)