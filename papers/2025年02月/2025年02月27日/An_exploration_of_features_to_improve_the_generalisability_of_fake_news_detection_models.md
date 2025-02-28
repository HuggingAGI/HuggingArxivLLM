# 探索如何通过特征优化提升虚假新闻检测模型的泛化能力

发布时间：2025年02月27日

`LLM应用`

> An exploration of features to improve the generalisability of fake news detection models

# 摘要

> 假新闻对全球构成风险，不仅影响选举，还传播错误信息，因此检测至关重要。现有的自然语言处理（NLP）和有监督机器学习方法在交叉验证中表现良好，但在跨数据集泛化时遇到困难，即使在同一领域内也是如此。这一问题源于粗略标注的训练数据，其中文章基于其发布者进行标注，引入了偏见，而基于Token的模型如TF-IDF和BERT对此类偏见敏感。尽管大型语言模型（LLMs）展现出潜力，但它们在假新闻检测中的应用仍有限。

本研究证明，即使从粗略标注的数据中，仍可提取有意义的特征以提升现实世界的鲁棒性。由于其对数据集偏见的敏感性较低，探索了风格特征（词汇、句法和语义）以及引入了新颖的社会货币化特征，捕捉假新闻背后的经济动机，例如广告、外部链接和社交媒体元素。研究基于粗略标注的NELA 2020-21数据集进行训练，并使用手动标注的Facebook URLs数据集进行评估，这是泛化能力的黄金标准。

结果显示，基于Token的模型在偏见数据上训练存在局限性，并为LLMs（如LLaMa）在这一领域的应用提供了稀缺证据。研究发现，风格和社会货币化特征比基于Token的方法和LLMs提供了更具泛化性的预测。统计和排列特征重要性分析进一步揭示了它们在提升性能和缓解数据集偏见方面的潜力，为改进假新闻检测提供了前进方向。


> Fake news poses global risks by influencing elections and spreading misinformation, making detection critical. Existing NLP and supervised Machine Learning methods perform well under cross-validation but struggle to generalise across datasets, even within the same domain. This issue stems from coarsely labelled training data, where articles are labelled based on their publisher, introducing biases that token-based models like TF-IDF and BERT are sensitive to. While Large Language Models (LLMs) offer promise, their application in fake news detection remains limited. This study demonstrates that meaningful features can still be extracted from coarsely labelled data to improve real-world robustness. Stylistic features-lexical, syntactic, and semantic-are explored due to their reduced sensitivity to dataset biases. Additionally, novel social-monetisation features are introduced, capturing economic incentives behind fake news, such as advertisements, external links, and social media elements. The study trains on the coarsely labelled NELA 2020-21 dataset and evaluates using the manually labelled Facebook URLs dataset, a gold standard for generalisability. Results highlight the limitations of token-based models trained on biased data and contribute to the scarce evidence on LLMs like LLaMa in this field. Findings indicate that stylistic and social-monetisation features offer more generalisable predictions than token-based methods and LLMs. Statistical and permutation feature importance analyses further reveal their potential to enhance performance and mitigate dataset biases, providing a path forward for improving fake news detection.

[Arxiv](https://arxiv.org/abs/2502.20299)