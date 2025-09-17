# 类比驱动的金融思维链（AD-FCoT）：面向金融情感分析的提示方法

发布时间：2025年09月15日

`LLM应用` `金融科技`

> Analogy-Driven Financial Chain-of-Thought (AD-FCoT): A Prompting Approach for Financial Sentiment Analysis

# 摘要

> 财经新闻情感分析对预测市场动态至关重要。随着人工智能技术（如大型语言模型，LLMs）的兴起——这些模型展现出强大的文本理解能力——人们对改进此类系统的兴趣再次高涨。然而，现有方法往往难以捕捉新闻中复杂的经济背景，且缺乏透明的推理过程，从而影响了其可靠性。为此，我们提出了类比驱动的财经思维链（AD-FCoT）——一个将类比推理与思维链（CoT）提示相结合的提示框架，专门用于历史财经新闻的情感预测。AD-FCoT引导LLMs将新事件与具有已知结果的相关历史场景进行类比，并将这些类比融入结构化的逐步推理链中。据我们所知，这是金融领域中首批明确将类比示例与CoT推理相结合的方法之一。AD-FCoT纯通过提示机制运行，无需额外训练数据或微调，而是借助模型的内部金融知识生成模仿人类分析推理的逻辑依据。在数千篇新闻文章上的实验表明，AD-FCoT在情感分类准确性上优于主流基线模型，且与市场回报的相关性显著提升。其生成的解释还与领域专业知识高度契合，为实际金融分析提供了可解释的洞见。

> Financial news sentiment analysis is crucial for anticipating market movements. With the rise of AI techniques such as Large Language Models (LLMs), which demonstrate strong text understanding capabilities, there has been renewed interest in enhancing these systems. Existing methods, however, often struggle to capture the complex economic context of news and lack transparent reasoning, which undermines their reliability. We propose Analogy-Driven Financial Chain-of-Thought (AD-FCoT), a prompting framework that integrates analogical reasoning with chain-of-thought (CoT) prompting for sentiment prediction on historical financial news. AD-FCoT guides LLMs to draw parallels between new events and relevant historical scenarios with known outcomes, embedding these analogies into a structured, step-by-step reasoning chain. To our knowledge, this is among the first approaches to explicitly combine analogical examples with CoT reasoning in finance. Operating purely through prompting, AD-FCoT requires no additional training data or fine-tuning and leverages the model's internal financial knowledge to generate rationales that mirror human analytical reasoning. Experiments on thousands of news articles show that AD-FCoT outperforms strong baselines in sentiment classification accuracy and achieves substantially higher correlation with market returns. Its generated explanations also align with domain expertise, providing interpretable insights suitable for real-world financial analysis.

[Arxiv](https://arxiv.org/abs/2509.12611)