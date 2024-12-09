# 一种借助 LLMs 来生成合成患者数据的文本转表格的方法

发布时间：2024年12月06日

`LLM应用` `数据生成`

> A text-to-tabular approach to generate synthetic patient data using LLMs

# 摘要

> 获取大规模高质量的医疗保健数据库，对于加快医学研究以及对疾病做出深刻洞察至关重要。但获取这类数据往往受患者隐私担忧、数据共享限制以及高成本的制约。为突破这些限制，合成患者数据成为了一种替代选择。然而，合成数据生成（SDG）方法通常依赖于基于原始数据训练的机器学习（ML）模型，这又回到了数据稀缺的问题。我们提出了一种生成合成表格患者数据的方法，无需访问原始数据，仅需对所需数据库进行描述。我们借助先前的医学知识和大型语言模型（LLMs）的上下文学习能力，即使在资源匮乏的情况下，也能生成逼真的患者数据。我们通过保真度、隐私和效用指标，将我们的方法与最先进的SDG模型进行了定量评估。结果显示，虽然LLMs的性能可能比不上基于原始数据训练的最先进模型，但它们能有效地生成具有良好临床相关性的逼真患者数据。一项消融研究突出了我们的提示中有助于高质量合成患者数据生成的关键要素。这种方法易于使用，不需要原始数据或高级ML技能，对于快速生成定制的患者数据、支持项目实施以及提供教育资源极具价值。

> Access to large-scale high-quality healthcare databases is key to accelerate medical research and make insightful discoveries about diseases. However, access to such data is often limited by patient privacy concerns, data sharing restrictions and high costs. To overcome these limitations, synthetic patient data has emerged as an alternative. However, synthetic data generation (SDG) methods typically rely on machine learning (ML) models trained on original data, leading back to the data scarcity problem. We propose an approach to generate synthetic tabular patient data that does not require access to the original data, but only a description of the desired database. We leverage prior medical knowledge and in-context learning capabilities of large language models (LLMs) to generate realistic patient data, even in a low-resource setting. We quantitatively evaluate our approach against state-of-the-art SDG models, using fidelity, privacy, and utility metrics. Our results show that while LLMs may not match the performance of state-of-the-art models trained on the original data, they effectively generate realistic patient data with well-preserved clinical correlations. An ablation study highlights key elements of our prompt contributing to high-quality synthetic patient data generation. This approach, which is easy to use and does not require original data or advanced ML skills, is particularly valuable for quickly generating custom-designed patient data, supporting project implementation and providing educational resources.

[Arxiv](https://arxiv.org/abs/2412.05153)