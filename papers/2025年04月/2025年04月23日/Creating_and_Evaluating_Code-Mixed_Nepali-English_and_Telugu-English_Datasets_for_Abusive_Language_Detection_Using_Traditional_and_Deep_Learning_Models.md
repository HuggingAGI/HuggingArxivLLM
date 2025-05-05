# 基于传统与深度学习模型，构建并评估用于滥用语言检测的尼泊尔英语与泰卢固英语代码混合数据集

发布时间：2025年04月23日

`LLM应用` `社交媒体`

> Creating and Evaluating Code-Mixed Nepali-English and Telugu-English Datasets for Abusive Language Detection Using Traditional and Deep Learning Models

# 摘要

> 随着社交媒体上多语言用户的增多，检测语言混杂文本中的滥用语言变得日益严峻。语言混杂交流中，用户在英语和母语之间无缝切换，这使得传统的滥用语言检测模型难以应对，因为攻击性内容可能依赖于上下文或被语言混合所掩盖。尽管针对英语和印地语等高资源语言的滥用语言检测已得到广泛研究，但泰卢固语和尼泊尔语等低资源语言仍代表性不足，导致有效的审核手段存在空白。本研究介绍了一个全新的手动标注数据集，包含2千条泰卢固语-英语和5千条尼泊尔语-英语混杂语言评论，分为滥用和非滥用两类，数据来源包括多个社交媒体平台。该数据集经过严格的预处理后，使用多种机器学习（ML）、深度学习（DL）和大型语言模型（LLMs）进行评估。我们尝试了包括逻辑回归、随机森林、支持向量机（SVM）、神经网络（NN）、LSTM、CNN和LLMs在内的多种模型，通过超参数调优优化性能，并采用10折交叉验证和统计显著性测试（t检验）进行评估。我们的研究结果揭示了在语言混杂环境下检测滥用语言的关键挑战，并提供了对计算方法的比较分析。本研究通过为泰卢固语-英语和尼泊尔语-英语混杂语言中的滥用语言检测建立基准，推动了针对低资源语言的自然语言处理技术发展。该数据集和研究结果可助力开发更强大的多语言社交媒体审核策略。

> With the growing presence of multilingual users on social media, detecting abusive language in code-mixed text has become increasingly challenging. Code-mixed communication, where users seamlessly switch between English and their native languages, poses difficulties for traditional abuse detection models, as offensive content may be context-dependent or obscured by linguistic blending. While abusive language detection has been extensively explored for high-resource languages like English and Hindi, low-resource languages such as Telugu and Nepali remain underrepresented, leaving gaps in effective moderation. In this study, we introduce a novel, manually annotated dataset of 2 thousand Telugu-English and 5 Nepali-English code-mixed comments, categorized as abusive and non-abusive, collected from various social media platforms. The dataset undergoes rigorous preprocessing before being evaluated across multiple Machine Learning (ML), Deep Learning (DL), and Large Language Models (LLMs). We experimented with models including Logistic Regression, Random Forest, Support Vector Machines (SVM), Neural Networks (NN), LSTM, CNN, and LLMs, optimizing their performance through hyperparameter tuning, and evaluate it using 10-fold cross-validation and statistical significance testing (t-test). Our findings provide key insights into the challenges of detecting abusive language in code-mixed settings and offer a comparative analysis of computational approaches. This study contributes to advancing NLP for low-resource languages by establishing benchmarks for abusive language detection in Telugu-English and Nepali-English code-mixed text. The dataset and insights can aid in the development of more robust moderation strategies for multilingual social media environments.

[Arxiv](https://arxiv.org/abs/2504.21026)