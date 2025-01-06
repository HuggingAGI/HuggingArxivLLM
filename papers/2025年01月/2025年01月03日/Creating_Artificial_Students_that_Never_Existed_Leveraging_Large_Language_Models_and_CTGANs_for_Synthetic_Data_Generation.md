# 创造虚拟学生：利用大型语言模型与CTGANs生成合成数据

发布时间：2025年01月03日

`LLM应用

解释：这篇论文主要探讨了利用大型语言模型（LLMs）生成合成表格数据的应用，特别是在学习分析领域的应用。虽然论文也提到了生成对抗网络（GANs），但重点在于LLMs的应用和效果评估。因此，将其分类为LLM应用是合适的。` `数据隐私`

> Creating Artificial Students that Never Existed: Leveraging Large Language Models and CTGANs for Synthetic Data Generation

# 摘要

> 本研究探讨了AI和深度学习技术，尤其是生成对抗网络（GANs）和大型语言模型（LLMs），在生成合成表格数据方面的潜力。高质量学生数据对学习分析至关重要，但隐私问题和全球数据保护法规限制了其使用。合成数据为此提供了新思路。我们利用CTGAN和三种LLMs（GPT2、DistilGPT2、DialoGPT）生成合成学生数据，结果表明这些方法能生成与真实数据高度相似的高质量数据集。通过一系列效用评估指标，我们验证了合成数据的统计和预测性能，并对比了不同生成器模型的表现，特别是LLMs的效果。本研究为学习分析领域提供了合成数据应用的宝贵见解，并为该领域的方法工具箱扩展奠定了基础。

> In this study, we explore the growing potential of AI and deep learning technologies, particularly Generative Adversarial Networks (GANs) and Large Language Models (LLMs), for generating synthetic tabular data. Access to quality students data is critical for advancing learning analytics, but privacy concerns and stricter data protection regulations worldwide limit their availability and usage. Synthetic data offers a promising alternative. We investigate whether synthetic data can be leveraged to create artificial students for serving learning analytics models. Using the popular GAN model CTGAN and three LLMs- GPT2, DistilGPT2, and DialoGPT, we generate synthetic tabular student data. Our results demonstrate the strong potential of these methods to produce high-quality synthetic datasets that resemble real students data. To validate our findings, we apply a comprehensive set of utility evaluation metrics to assess the statistical and predictive performance of the synthetic data and compare the different generator models used, specially the performance of LLMs. Our study aims to provide the learning analytics community with valuable insights into the use of synthetic data, laying the groundwork for expanding the field methodological toolbox with new innovative approaches for learning analytics data generation.

[Arxiv](https://arxiv.org/abs/2501.01793)