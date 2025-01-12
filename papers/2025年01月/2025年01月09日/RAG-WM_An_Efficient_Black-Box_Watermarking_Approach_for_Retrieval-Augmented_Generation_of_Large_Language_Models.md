# RAG-WM: 大型语言模型检索增强生成的高效黑盒水印方案

发布时间：2025年01月09日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的知识产权保护问题，并提出了一种名为RAG-WM的黑盒“知识水印”方法。论文的核心内容围绕RAG系统的安全性、知识产权保护以及水印技术的应用，因此应归类为RAG。` `知识产权保护` `信息安全`

> RAG-WM: An Efficient Black-Box Watermarking Approach for Retrieval-Augmented Generation of Large Language Models

# 摘要

> 近年来，检索增强生成（RAG）在增强大型语言模型（LLMs）于特定领域、知识密集型和隐私敏感任务中的表现方面取得了显著成功。然而，攻击者可能窃取这些RAG并用于商业目的，因此检测知识产权（IP）侵权行为至关重要。现有的所有权保护方案（如水印）主要针对关系数据库和文本设计，无法直接应用于RAG。这是因为关系数据库水印需要白盒访问来检测IP侵权，而RAG的知识库难以满足这一条件。此外，对手部署的LLMs的后处理通常会破坏文本水印信息。为解决这些问题，我们提出了一种名为RAG-WM的黑盒“知识水印”方法，用于检测RAG的IP侵权。RAG-WM采用多LLM交互框架，包括水印生成器、影子LLM和RAG以及水印鉴别器，基于水印实体关系元组生成水印文本并注入目标RAG。我们在四个基准LLMs上对RAG-WM进行了评估，涵盖三个特定领域和两个隐私敏感任务。实验结果表明，RAG-WM能够有效检测各种部署LLMs中的被盗RAG，并对改写、无关内容删除、知识插入和知识扩展攻击表现出鲁棒性。此外，RAG-WM还能规避水印检测方法，展现了其在RAG系统IP侵权检测中的广阔应用前景。

> In recent years, tremendous success has been witnessed in Retrieval-Augmented Generation (RAG), widely used to enhance Large Language Models (LLMs) in domain-specific, knowledge-intensive, and privacy-sensitive tasks. However, attackers may steal those valuable RAGs and deploy or commercialize them, making it essential to detect Intellectual Property (IP) infringement. Most existing ownership protection solutions, such as watermarks, are designed for relational databases and texts. They cannot be directly applied to RAGs because relational database watermarks require white-box access to detect IP infringement, which is unrealistic for the knowledge base in RAGs. Meanwhile, post-processing by the adversary's deployed LLMs typically destructs text watermark information. To address those problems, we propose a novel black-box "knowledge watermark" approach, named RAG-WM, to detect IP infringement of RAGs. RAG-WM uses a multi-LLM interaction framework, comprising a Watermark Generator, Shadow LLM & RAG, and Watermark Discriminator, to create watermark texts based on watermark entity-relationship tuples and inject them into the target RAG. We evaluate RAG-WM across three domain-specific and two privacy-sensitive tasks on four benchmark LLMs. Experimental results show that RAG-WM effectively detects the stolen RAGs in various deployed LLMs. Furthermore, RAG-WM is robust against paraphrasing, unrelated content removal, knowledge insertion, and knowledge expansion attacks. Lastly, RAG-WM can also evade watermark detection approaches, highlighting its promising application in detecting IP infringement of RAG systems.

[Arxiv](https://arxiv.org/abs/2501.05249)