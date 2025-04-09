# LLM×MapReduce-V2：熵驱动卷积测试时间缩放，生成超长资源长文

发布时间：2025年04月08日

`LLM应用` `文本生成`

> LLM$\times$MapReduce-V2: Entropy-Driven Convolutional Test-Time Scaling for Generating Long-Form Articles from Extremely Long Resources

# 摘要

> 长文本生成在广泛的应用场景中发挥着重要作用，主要分为短文本到长文本生成和长文本到长文本生成两大类。尽管短文本到长文本生成已受到较多关注，但从超长资源中生成长文本仍是一个相对未被充分探索的领域。长文本到长文本生成的核心挑战在于如何有效整合和分析来自大量输入的相关信息，这一难题目前仍困扰着现有的大型语言模型 (LLMs)。本文中，我们提出了 LLM×MapReduce-V2，这是一种旨在增强 LLMs 处理超长输入能力的新型测试时间缩放策略。受卷积神经网络的启发，LLM×MapReduce-V2 通过叠加卷积缩放层，逐步扩展对输入材料的理解，将局部特征逐步整合到更高层次的全局表示中。实验结果表明，我们的方法显著提升了 LLMs 处理长输入的能力，并能够生成连贯、信息丰富的长篇文章，在处理长输入和生成连贯、信息丰富的长篇文章方面显著优于多个代表性基线。


> Long-form generation is crucial for a wide range of practical applications, typically categorized into short-to-long and long-to-long generation. While short-to-long generations have received considerable attention, generating long texts from extremely long resources remains relatively underexplored. The primary challenge in long-to-long generation lies in effectively integrating and analyzing relevant information from extensive inputs, which remains difficult for current large language models (LLMs). In this paper, we propose LLM$\times$MapReduce-V2, a novel test-time scaling strategy designed to enhance the ability of LLMs to process extremely long inputs. Drawing inspiration from convolutional neural networks, which iteratively integrate local features into higher-level global representations, LLM$\times$MapReduce-V2 utilizes stacked convolutional scaling layers to progressively expand the understanding of input materials. Both quantitative and qualitative experimental results demonstrate that our approach substantially enhances the ability of LLMs to process long inputs and generate coherent, informative long-form articles, outperforming several representative baselines.

[Arxiv](https://arxiv.org/abs/2504.05732)