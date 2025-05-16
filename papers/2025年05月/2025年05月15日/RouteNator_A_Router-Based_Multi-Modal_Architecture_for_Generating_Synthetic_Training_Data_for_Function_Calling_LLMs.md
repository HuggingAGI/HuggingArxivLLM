# RouteNator：基于路由器的多模态架构，专为函数调用型LLMs打造合成训练数据

发布时间：2025年05月15日

`LLM应用` `数字内容创作` `数字工具`

> RouteNator: A Router-Based Multi-Modal Architecture for Generating Synthetic Training Data for Function Calling LLMs

# 摘要

> 本文探讨了在缺乏真实用户交互数据的情况下，如何对大型语言模型（LLMs）进行微调以实现功能调用任务。在数字内容创作工具中，用户通过自然语言查询表达需求，这些查询需映射到API调用。由于特定任务的真实数据稀缺且受隐私限制，生成合成数据成为必要。现有合成数据生成方法在多样性和复杂性上不足，无法复制真实数据分布，导致LLM微调效果不佳。我们提出了一种基于路由的新型架构，利用内容元数据、结构化知识图谱以及文本到文本和视觉到文本的语言模型，生成高质量的合成训练数据。该架构的灵活路由机制使生成的合成数据能够匹配真实世界的数据分布，克服了传统方法的局限。在真实用户查询的全面评估中，模型在功能分类准确性和API参数选择上均有显著提升。使用我们的合成数据微调后的模型在功能调用任务中表现优于传统方法，树立了新的基准。

> This paper addresses fine-tuning Large Language Models (LLMs) for function calling tasks when real user interaction data is unavailable. In digital content creation tools, where users express their needs through natural language queries that must be mapped to API calls, the lack of real-world task-specific data and privacy constraints for training on it necessitate synthetic data generation. Existing approaches to synthetic data generation fall short in diversity and complexity, failing to replicate real-world data distributions and leading to suboptimal performance after LLM fine-tuning. We present a novel router-based architecture that leverages domain resources like content metadata and structured knowledge graphs, along with text-to-text and vision-to-text language models to generate high-quality synthetic training data. Our architecture's flexible routing mechanism enables synthetic data generation that matches observed real-world distributions, addressing a fundamental limitation of traditional approaches. Evaluation on a comprehensive set of real user queries demonstrates significant improvements in both function classification accuracy and API parameter selection. Models fine-tuned with our synthetic data consistently outperform traditional approaches, establishing new benchmarks for function calling tasks.

[Arxiv](https://arxiv.org/abs/2505.10495)