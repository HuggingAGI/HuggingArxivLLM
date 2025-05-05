# 如何在基于LLM的产品推荐中平衡隐私与实用性？

发布时间：2025年05月01日

`LLM应用` `推荐系统` `电子商务`

> Preserving Privacy and Utility in LLM-Based Product Recommendations

# 摘要

> 基于大型语言模型（LLM）的推荐系统通过处理用户交互和偏好，利用强大的语言模型生成个性化建议。与依赖结构化数据和协同过滤的传统推荐系统不同，基于LLM的模型处理文本和上下文信息，通常使用基于云的基础设施。然而，这引发了隐私问题，因为用户数据被传输到远程服务器，增加了数据暴露的风险并减少了对个人信息的控制。为了解决这个问题，我们提出了一种混合隐私保护推荐框架，该框架将敏感数据与非敏感数据分离，并仅将后者与云共享以利用LLM驱动的推荐。为了恢复与模糊化敏感数据相关的丢失推荐，我们设计了一个去模糊模块，用于在本地重建敏感推荐。在现实世界的电子商务数据集上的实验表明，我们的框架几乎达到了与将所有数据与LLM共享的系统相同的推荐效用，同时在很大程度上保留了隐私。与仅使用模糊化技术相比，我们的方法提高了HR@10分数和类别分布的一致性，提供了更好的隐私和推荐质量平衡。此外，我们的方法在消费级硬件上高效运行，使隐私感知的LLM驱动推荐系统在实际应用中成为可能。

> Large Language Model (LLM)-based recommendation systems leverage powerful language models to generate personalized suggestions by processing user interactions and preferences. Unlike traditional recommendation systems that rely on structured data and collaborative filtering, LLM-based models process textual and contextual information, often using cloud-based infrastructure. This raises privacy concerns, as user data is transmitted to remote servers, increasing the risk of exposure and reducing control over personal information. To address this, we propose a hybrid privacy-preserving recommendation framework which separates sensitive from nonsensitive data and only shares the latter with the cloud to harness LLM-powered recommendations. To restore lost recommendations related to obfuscated sensitive data, we design a de-obfuscation module that reconstructs sensitive recommendations locally. Experiments on real-world e-commerce datasets show that our framework achieves almost the same recommendation utility with a system which shares all data with an LLM, while preserving privacy to a large extend. Compared to obfuscation-only techniques, our approach improves HR@10 scores and category distribution alignment, offering a better balance between privacy and recommendation quality. Furthermore, our method runs efficiently on consumer-grade hardware, making privacy-aware LLM-based recommendation systems practical for real-world use.

[Arxiv](https://arxiv.org/abs/2505.00951)