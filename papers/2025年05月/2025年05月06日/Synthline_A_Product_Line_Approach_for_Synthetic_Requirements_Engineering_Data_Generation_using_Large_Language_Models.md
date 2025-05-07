# # Synthline：基于大型语言模型的合成需求工程数据生成的产品线方法

发布时间：2025年05月06日

`LLM应用` `需求工程` `软件工程`

> Synthline: A Product Line Approach for Synthetic Requirements Engineering Data Generation using Large Language Models

# 摘要

> 现代需求工程 (RE) 虽然高度依赖自然语言处理和机器学习 (ML) 技术，但其效果受限于高质量数据集的稀缺性。本文提出了一种基于产品线 (PL) 的方法——Synthline，利用大型语言模型系统地为基于分类的用例生成合成 RE 数据。通过在利用 ML 识别需求规格缺陷的背景下进行实证评估，我们研究了生成数据的多样性和其对下游模型训练的实用性。分析表明，尽管合成数据集的多样性低于真实数据，但它们足够好，可以用作可行的训练资源。此外，我们的评估表明，结合合成数据和真实数据可以带来显著的性能提升。具体而言，混合方法在精确度上提高了 85%，召回率提高了 2 倍，相比仅使用真实数据训练的模型。这些发现展示了基于 PL 的合成数据生成在缓解 RE 数据稀缺性方面的潜力。我们公开了我们的实现和生成的数据集，以支持可重复性和该领域的进展。

> While modern Requirements Engineering (RE) heavily relies on natural language processing and Machine Learning (ML) techniques, their effectiveness is limited by the scarcity of high-quality datasets. This paper introduces Synthline, a Product Line (PL) approach that leverages Large Language Models to systematically generate synthetic RE data for classification-based use cases. Through an empirical evaluation conducted in the context of using ML for the identification of requirements specification defects, we investigated both the diversity of the generated data and its utility for training downstream models. Our analysis reveals that while synthetic datasets exhibit less diversity than real data, they are good enough to serve as viable training resources. Moreover, our evaluation shows that combining synthetic and real data leads to substantial performance improvements. Specifically, hybrid approaches achieve up to 85% improvement in precision and a 2x increase in recall compared to models trained exclusively on real data. These findings demonstrate the potential of PL-based synthetic data generation to address data scarcity in RE. We make both our implementation and generated datasets publicly available to support reproducibility and advancement in the field.

[Arxiv](https://arxiv.org/abs/2505.03265)