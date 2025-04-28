# # 标题
跨域推荐：大型语言模型助力跨领域序列推荐

发布时间：2025年04月25日

`LLM应用` `推荐系统` `电子商务`

> Bridge the Domains: Large Language Models Enhanced Cross-domain Sequential Recommendation

# 摘要

> 跨领域序列推荐（CDSR）旨在从用户跨领域交互中提取偏好。尽管CDSR取得了一些进展，但仍面临两大难题：重叠困境和过渡复杂性。前者指现有方法严重依赖用户在所有领域的交互记录来学习跨域项目关系，降低了实用性。后者则指从混合行为序列中学习复杂过渡模式的困难。大型语言模型（LLMs）凭借强大的表示和推理能力，有望通过从语义视角连接项目并捕捉用户偏好来解决这两个问题。因此，我们提出了一种基于LLMs的跨领域序列推荐模型（LLM4CDSR）。为获取语义项目关系，我们首先提出了一种基于LLMs的统一表示模块来表示项目。然后，设计了一个带有对比正则化的可训练适配器来适应CDSR任务。此外，还设计了一个层次化的LLMs画像模块来总结用户的跨域偏好。最后，将这两个模块集成到提出的三线框架中以生成推荐。我们在三个公开的跨域数据集上进行了广泛的实验，验证了LLM4CDSR的有效性，并已将代码在线发布。

> Cross-domain Sequential Recommendation (CDSR) aims to extract the preference from the user's historical interactions across various domains. Despite some progress in CDSR, two problems set the barrier for further advancements, i.e., overlap dilemma and transition complexity. The former means existing CDSR methods severely rely on users who own interactions on all domains to learn cross-domain item relationships, compromising the practicability. The latter refers to the difficulties in learning the complex transition patterns from the mixed behavior sequences. With powerful representation and reasoning abilities, Large Language Models (LLMs) are promising to address these two problems by bridging the items and capturing the user's preferences from a semantic view. Therefore, we propose an LLMs Enhanced Cross-domain Sequential Recommendation model (LLM4CDSR). To obtain the semantic item relationships, we first propose an LLM-based unified representation module to represent items. Then, a trainable adapter with contrastive regularization is designed to adapt the CDSR task. Besides, a hierarchical LLMs profiling module is designed to summarize user cross-domain preferences. Finally, these two modules are integrated into the proposed tri-thread framework to derive recommendations. We have conducted extensive experiments on three public cross-domain datasets, validating the effectiveness of LLM4CDSR. We have released the code online.

[Arxiv](https://arxiv.org/abs/2504.18383)