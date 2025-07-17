# # Text-ADBench：基于大语言模型嵌入的文本异常检测基准测试

发布时间：2025年07月16日

`LLM应用` `信息安全`

> Text-ADBench: Text Anomaly Detection Benchmark based on LLMs Embedding

# 摘要

> 文本异常检测是自然语言处理中的关键任务，应用广泛，涵盖欺诈检测、错误信息识别、垃圾信息检测和内容审核等多个领域。尽管大型语言模型和异常检测算法取得了显著进展，但缺乏标准化和全面的基准来评估现有的文本异常检测方法，这限制了严格比较和创新方法的发展。本研究进行了一项全面的实证研究，引入了用于文本异常检测的基准，利用来自各种预训练语言模型的嵌入，涵盖广泛的文本数据集。我们的工作通过整合早期语言模型（如GloVe和BERT）、多个大型语言模型（包括LLaMa-2、LLama-3、Mistral和OpenAI的不同版本）、多领域文本数据集（如新闻、社交媒体和科学出版物）以及全面的评估指标（如AUROC和AUPRC），系统地评估了基于嵌入的文本异常检测的有效性。实验结果揭示了一个关键的实证见解：嵌入质量对异常检测效果有显著影响。有趣的是，基于深度学习的方法在利用LLM生成的嵌入时，并没有显示出比传统的浅层算法（如KNN和孤立森林）更好的性能优势。此外，我们在跨模型性能矩阵中观察到强烈的低秩特征，这为实际应用中快速模型评估和选择提供了一种高效的策略。为了推动这一领域的进一步研究，我们开源了基准工具包，其中包括不同模型的所有嵌入和代码（https://github.com/jicongfan/Text-Anomaly-Detection-Benchmark），为未来在健壮和可扩展的文本异常检测系统方面的研究奠定了基础。

> Text anomaly detection is a critical task in natural language processing (NLP), with applications spanning fraud detection, misinformation identification, spam detection and content moderation, etc. Despite significant advances in large language models (LLMs) and anomaly detection algorithms, the absence of standardized and comprehensive benchmarks for evaluating the existing anomaly detection methods on text data limits rigorous comparison and development of innovative approaches. This work performs a comprehensive empirical study and introduces a benchmark for text anomaly detection, leveraging embeddings from diverse pre-trained language models across a wide array of text datasets. Our work systematically evaluates the effectiveness of embedding-based text anomaly detection by incorporating (1) early language models (GloVe, BERT); (2) multiple LLMs (LLaMa-2, LLama-3, Mistral, OpenAI (small, ada, large)); (3) multi-domain text datasets (news, social media, scientific publications); (4) comprehensive evaluation metrics (AUROC, AUPRC). Our experiments reveal a critical empirical insight: embedding quality significantly governs anomaly detection efficacy, and deep learning-based approaches demonstrate no performance advantage over conventional shallow algorithms (e.g., KNN, Isolation Forest) when leveraging LLM-derived embeddings.In addition, we observe strongly low-rank characteristics in cross-model performance matrices, which enables an efficient strategy for rapid model evaluation (or embedding evaluation) and selection in practical applications. Furthermore, by open-sourcing our benchmark toolkit that includes all embeddings from different models and code at https://github.com/jicongfan/Text-Anomaly-Detection-Benchmark, this work provides a foundation for future research in robust and scalable text anomaly detection systems.

[Arxiv](https://arxiv.org/abs/2507.12295)