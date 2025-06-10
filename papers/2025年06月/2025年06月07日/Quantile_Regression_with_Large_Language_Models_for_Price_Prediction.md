# 分位数回归结合大型语言模型用于价格预测

发布时间：2025年06月07日

`LLM应用` `房地产` `统计学`

> Quantile Regression with Large Language Models for Price Prediction

# 摘要

> 大型语言模型（LLMs）在回归等结构化预测任务中展现出潜力，但现有方法主要集中在点估计，且缺乏系统性比较。我们研究了LLMs在无结构输入上的回归应用，重点关注文本到分布的预测任务，例如价格估计，其中对文本的细微理解与不确定性量化都至关重要。我们提出了一种新型的分位数回归方法，使LLMs能够生成完整的预测分布，超越传统的点估计方法。通过在三个多样化的房价预测数据集上进行广泛实验，我们证明了经过分位数头部微调的Mistral-7B模型在点估计和分布估计方面均显著优于传统方法，根据三个公认的准确性指标和分布校准指标进行评估。我们对LLM方法、模型架构、训练方法和数据规模的系统性比较表明，Mistral-7B在编码器架构、基于嵌入的方法和少样本学习方法中表现最为突出。我们的实验还展示了LLM辅助标签修正在实现无系统偏差的人类级别准确性方面的有效性。我们整理的数据集已发布在https://github.com/vnik18/llm-price-quantile-reg/，以支持未来研究。

> Large Language Models (LLMs) have shown promise in structured prediction tasks, including regression, but existing approaches primarily focus on point estimates and lack systematic comparison across different methods. We investigate probabilistic regression using LLMs for unstructured inputs, addressing challenging text-to-distribution prediction tasks such as price estimation where both nuanced text understanding and uncertainty quantification are critical. We propose a novel quantile regression approach that enables LLMs to produce full predictive distributions, improving upon traditional point estimates. Through extensive experiments across three diverse price prediction datasets, we demonstrate that a Mistral-7B model fine-tuned with quantile heads significantly outperforms traditional approaches for both point and distributional estimations, as measured by three established metrics each for prediction accuracy and distributional calibration. Our systematic comparison of LLM approaches, model architectures, training approaches, and data scaling reveals that Mistral-7B consistently outperforms encoder architectures, embedding-based methods, and few-shot learning methods. Our experiments also reveal the effectiveness of LLM-assisted label correction in achieving human-level accuracy without systematic bias. Our curated datasets are made available at https://github.com/vnik18/llm-price-quantile-reg/ to support future research.

[Arxiv](https://arxiv.org/abs/2506.06657)