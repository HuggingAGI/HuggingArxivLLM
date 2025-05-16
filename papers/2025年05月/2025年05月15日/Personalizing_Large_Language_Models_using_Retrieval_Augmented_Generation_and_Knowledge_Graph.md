# 结合检索增强生成与知识图谱的大型语言模型个性化方法

发布时间：2025年05月15日

`RAG` `日历管理` `聊天机器人`

> Personalizing Large Language Models using Retrieval Augmented Generation and Knowledge Graph

# 摘要

> 大型语言模型（LLMs）的出现使得众多应用，包括生成查询响应，能够在聊天机器人和其他对话式助手中得到利用。然而，由于LLMs在大量数据上进行了训练，常常会导致严重的过拟合，生成额外的和不正确的数据，从而在输出生成过程中产生幻觉。此类问题的一个根本原因是未能及时向LLMs提供事实准确且个性化的信息。本文中，我们提出了一种方法，通过引入基于知识图谱（KGs）的检索增强生成（RAG）来解决这些问题，从而协助LLMs生成个性化响应，以满足用户需求。KGs的优势在于能够以结构化的方式存储持续更新的事实信息。虽然我们的KGs可以用于多种需要频繁更新的个人数据，例如日历、联系人和位置数据，但在本文中，我们专注于日历数据。我们的实验结果表明，与仅将个人数据作为文本输入的基线LLMs相比，我们的方法在理解个人信息和生成准确响应方面表现显著更好，同时响应时间也适度减少。

> The advent of large language models (LLMs) has allowed numerous applications, including the generation of queried responses, to be leveraged in chatbots and other conversational assistants. Being trained on a plethora of data, LLMs often undergo high levels of over-fitting, resulting in the generation of extra and incorrect data, thus causing hallucinations in output generation. One of the root causes of such problems is the lack of timely, factual, and personalized information fed to the LLM. In this paper, we propose an approach to address these problems by introducing retrieval augmented generation (RAG) using knowledge graphs (KGs) to assist the LLM in personalized response generation tailored to the users. KGs have the advantage of storing continuously updated factual information in a structured way. While our KGs can be used for a variety of frequently updated personal data, such as calendar, contact, and location data, we focus on calendar data in this paper. Our experimental results show that our approach works significantly better in understanding personal information and generating accurate responses compared to the baseline LLMs using personal data as text inputs, with a moderate reduction in response time.

[Arxiv](https://arxiv.org/abs/2505.09945)