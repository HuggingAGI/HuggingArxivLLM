# 大型语言模型生成的音乐偏好档案中的偏见分析

发布时间：2025年07月22日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在推荐系统中的应用，特别是自动生成自然语言用户口味档案。虽然它讨论了LLMs在生成档案时可能面临的挑战，如偏见和档案质量，但其主要关注点是LLMs在实际应用中的效果和用户反馈，属于LLM应用的范畴。` `推荐系统` `个性化推荐`

> Biases in LLM-Generated Musical Taste Profiles for Recommendation

# 摘要

> 大型语言模型（LLMs）在推荐系统中的一项极具前景的应用是从消费数据自动生成自然语言（NL）用户口味档案。这些档案不仅提供了比传统协同过滤方法更透明、更可控的用户画像，还为个性化推荐系统注入了新的活力。然而，用户是否认为这些档案准确反映了他们的口味偏好，仍是影响推荐系统信任度和用户体验的关键问题。此外，LLMs在生成这些档案时可能会受到社会和数据偏见的影响，导致档案质量因用户和项目特征而异。本文以音乐流媒体为研究背景，探讨了在面对大规模、文化多样化的音乐目录时，个性化推荐所面临的挑战。我们开展了一项用户研究，参与者根据自己的听歌历史对生成的NL档案进行了评分。通过分析用户属性（如主流程度、口味多样性）和项目特征（如流派、原产国）对档案认同的影响，我们揭示了LLM生成档案在个性化推荐中的潜力与局限性。此外，我们还比较了这些模式在下游推荐任务中的表现，为未来的研究和应用提供了有价值的见解。

> One particularly promising use case of Large Language Models (LLMs) for recommendation is the automatic generation of Natural Language (NL) user taste profiles from consumption data. These profiles offer interpretable and editable alternatives to opaque collaborative filtering representations, enabling greater transparency and user control. However, it remains unclear whether users consider these profiles to be an accurate representation of their taste, which is crucial for trust and usability. Moreover, because LLMs inherit societal and data-driven biases, profile quality may systematically vary across user and item characteristics. In this paper, we study this issue in the context of music streaming, where personalization is challenged by a large and culturally diverse catalog. We conduct a user study in which participants rate NL profiles generated from their own listening histories. We analyze whether identification with the profiles is biased by user attributes (e.g., mainstreamness, taste diversity) and item features (e.g., genre, country of origin). We also compare these patterns to those observed when using the profiles in a downstream recommendation task. Our findings highlight both the potential and limitations of scrutable, LLM-based profiling in personalized systems.

[Arxiv](https://arxiv.org/abs/2507.16708)