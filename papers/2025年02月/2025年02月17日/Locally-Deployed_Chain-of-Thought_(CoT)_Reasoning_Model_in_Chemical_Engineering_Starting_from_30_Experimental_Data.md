# # 标题
基于30个实验数据，本地部署的链式思维（CoT）推理模型在化学工程中的应用

发布时间：2025年02月17日

`LLM应用` `化学工程` `分子性质预测`

> Locally-Deployed Chain-of-Thought (CoT) Reasoning Model in Chemical Engineering: Starting from 30 Experimental Data

# 摘要

> 在化学工程领域，传统数据处理和预测方法面临着巨大挑战。机器学习和大型语言模型（LLMs）也有各自的技术局限。本文研究了Chain-of-Thought（CoT）推理模型在化学工程中的应用，从30个实验数据点入手。通过将高斯过程和随机森林等传统代理模型与DeepSeek-R1等强大的LLMs相结合，提出了一种分层架构。研究了两种CoT构建方法：大型语言模型-链式推理（LLM-CoT）和机器学习-大型语言模型-链式推理（ML-LLM-CoT）。LLM-CoT结合了局部模型DeepSeek-r1:14b和Qwen2:7b，借助Ollama平台。ML-LLM-CoT则将预训练的高斯ML模型与基于LLM的CoT框架相结合。实验结果显示，在构建过程中，ML-LLM-CoT更具优势。它仅需对2个点进行重新思考，总重新思考次数为4次，而LLM-CoT需要对5个点进行重新思考，总重新思考次数达34次。在对20个结构差异显著的分子溶解度进行预测时，高斯模型、LLM-CoT和ML-LLM-CoT预测偏差超过100%的分子数量分别为7、6和4。这些结果表明，ML-LLM-CoT在控制高偏差分子数量、优化平均偏差以及提高溶解度判断成功率方面表现更优，为化学工程和分子性质预测提供了一种更可靠的方法。本研究突破了传统方法的局限性，为化学工程中的快速性质预测和工艺优化提供了新的解决方案。

> In the field of chemical engineering, traditional data-processing and prediction methods face significant challenges. Machine-learning and large-language models (LLMs) also have their respective limitations. This paper explores the application of the Chain-of-Thought (CoT) reasoning model in chemical engineering, starting from 30 experimental data points. By integrating traditional surrogate models like Gaussian processes and random forests with powerful LLMs such as DeepSeek-R1, a hierarchical architecture is proposed. Two CoT-building methods, Large Language Model-Chain of Thought (LLM-CoT) and Machine Learning-Large Language Model-Chain of Thought (ML-LLM-CoT), are studied. The LLM-CoT combines local models DeepSeek-r1:14b and Qwen2:7b with Ollama. The ML-LLM-CoT integrates a pre-trained Gaussian ML model with the LLM-based CoT framework. Our results show that during construction, ML-LLM-CoT is more efficient. It only has 2 points that require rethink and a total of 4 rethink times, while LLM-CoT has 5 points that need to be re-thought and 34 total rethink times. In predicting the solubility of 20 molecules with dissimilar structures, the number of molecules with a prediction deviation higher than 100\% for the Gaussian model, LLM-CoT, and ML-LLM-CoT is 7, 6, and 4 respectively. These results indicate that ML-LLM-CoT performs better in controlling the number of high-deviation molecules, optimizing the average deviation, and achieving a higher success rate in solubility judgment, providing a more reliable method for chemical engineering and molecular property prediction. This study breaks through the limitations of traditional methods and offers new solutions for rapid property prediction and process optimization in chemical engineering.

[Arxiv](https://arxiv.org/abs/2502.12383)