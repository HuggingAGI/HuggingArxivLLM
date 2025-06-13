# 超越是非：检索增强的层次分析，用于分析微妙主张

发布时间：2025年06月12日

`RAG`

> Beyond True or False: Retrieval-Augmented Hierarchical Analysis of Nuanced Claims

# 摘要

> 个人或机构提出的主张往往具有细微差别，很难明确地将其简单归类为完全“真实”或“虚假”——这种情况在科学和政治主张中尤为常见。然而，一个主张（例如，“疫苗A比疫苗B更好”）可以被分解为其核心方面和次要方面（例如，效力、安全性和分发），这些方面单独来看更容易进行验证。这使得我们能够构建一个更加全面、结构化的响应，为某一特定问题提供多角度的综合视角，同时允许读者在主张中优先关注自己感兴趣的特定角度（例如，疫苗对儿童的安全性）。因此，我们提出了ClaimSpect，这是一个基于检索增强生成的框架，用于自动构建在处理主张时通常会考虑的方面层次结构，并通过语料库特定的视角来丰富这些方面。该框架将输入语料库分层次划分，以检索相关段落，这些段落有助于发现新的次要方面。此外，这些段落能够揭示针对主张某一特定方面的不同观点（例如，支持、中立或反对）及其各自的普遍程度（例如，“有多少生物医学论文认为疫苗A比疫苗B更易于运输？”）。我们将ClaimSpect应用于我们构建的数据集中包含的各种真实世界科学和政治主张，展示了其在分解细微主张和在语料库中表示观点方面的稳健性和准确性。通过真实世界的案例研究和人工评估，我们验证了其在多个基线模型上的有效性。

> Claims made by individuals or entities are oftentimes nuanced and cannot be clearly labeled as entirely "true" or "false" -- as is frequently the case with scientific and political claims. However, a claim (e.g., "vaccine A is better than vaccine B") can be dissected into its integral aspects and sub-aspects (e.g., efficacy, safety, distribution), which are individually easier to validate. This enables a more comprehensive, structured response that provides a well-rounded perspective on a given problem while also allowing the reader to prioritize specific angles of interest within the claim (e.g., safety towards children). Thus, we propose ClaimSpect, a retrieval-augmented generation-based framework for automatically constructing a hierarchy of aspects typically considered when addressing a claim and enriching them with corpus-specific perspectives. This structure hierarchically partitions an input corpus to retrieve relevant segments, which assist in discovering new sub-aspects. Moreover, these segments enable the discovery of varying perspectives towards an aspect of the claim (e.g., support, neutral, or oppose) and their respective prevalence (e.g., "how many biomedical papers believe vaccine A is more transportable than B?"). We apply ClaimSpect to a wide variety of real-world scientific and political claims featured in our constructed dataset, showcasing its robustness and accuracy in deconstructing a nuanced claim and representing perspectives within a corpus. Through real-world case studies and human evaluation, we validate its effectiveness over multiple baselines.

[Arxiv](https://arxiv.org/abs/2506.10728)