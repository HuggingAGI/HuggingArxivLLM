# FinBloom：实时金融数据赋能大型语言模型的知识增强

发布时间：2025年02月04日

`LLM应用

摘要中提到的论文主要探讨了如何将大型语言模型（LLMs）应用于金融领域，通过构建特定的金融数据集和训练定制模型来提升模型在实时信息处理中的表现。这种方法属于将LLMs应用于实际任务，因此归类为LLM应用。` `问答系统`

> FinBloom: Knowledge Grounding Large Language Model with Real-time Financial Data

# 摘要

> 大型语言模型（LLMs）擅长生成类人回应，但在需要实时信息的交互任务中表现欠佳。这一问题在金融领域尤为突出，因为模型必须获取最新信息（如新闻或价格波动）来支持决策。为解决这一问题，我们推出了Financial Agent，这是一种基于LLMs的知识 grounding 方法，能够利用实时文本和表格数据处理金融查询。我们的贡献包括：
1. 开发了一个包含50,000多个金融查询及其所需上下文的金融上下文数据集。
2. 使用来自路透社和德国通讯社的1400万篇金融新闻文章，以及1200万份美国证券交易委员会（SEC）文件，训练了一个70亿参数的定制化LLM——FinBloom 7B。
3. 利用金融上下文数据集对FinBloom 7B进行微调，使其成为金融代理，能够生成相关金融上下文并高效检索实时数据以回答用户查询。

通过减少延迟并消除用户手动提供准确数据的需要，我们的方法显著提升了LLMs处理动态金融任务的能力。该方法使实时金融决策、算法交易和其他相关任务更加流畅，特别适用于数据流高速变化的场景。

> Large language models (LLMs) excel at generating human-like responses but often struggle with interactive tasks that require access to real-time information. This limitation poses challenges in finance, where models must access up-to-date information, such as recent news or price movements, to support decision-making. To address this, we introduce Financial Agent, a knowledge-grounding approach for LLMs to handle financial queries using real-time text and tabular data. Our contributions are threefold: First, we develop a Financial Context Dataset of over 50,000 financial queries paired with the required context. Second, we train FinBloom 7B, a custom 7 billion parameter LLM, on 14 million financial news articles from Reuters and Deutsche Presse-Agentur, alongside 12 million Securities and Exchange Commission (SEC) filings. Third, we fine-tune FinBloom 7B using the Financial Context Dataset to serve as a Financial Agent. This agent generates relevant financial context, enabling efficient real-time data retrieval to answer user queries. By reducing latency and eliminating the need for users to manually provide accurate data, our approach significantly enhances the capability of LLMs to handle dynamic financial tasks. Our proposed approach makes real-time financial decisions, algorithmic trading and other related tasks streamlined, and is valuable in contexts with high-velocity data flows.

[Arxiv](https://arxiv.org/abs/2502.18471)